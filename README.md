<html lang="en-US">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <img src = "DTE_Bank_wxO.png"
    	width="auto" height="1200"
         alt = "New Watson Assistant Bank" />

</head>

<!-- add your script here -->
<script>
  window.watsonAssistantChatOptions = {
  integrationID: "ce902af2-0c04-4f27-b344-81dbae9880dd", // The ID of this integration.
  region: "wxo-us-south", // The region your integration is hosted in.
  serviceInstanceID: "ba479963-b193-41b3-8a65-fb8c95245a68", // The ID of your service instance.
  orchestrateUIAgentExtensions: false, // If you wish to enable optional UI Agent extensions.
  onLoad: async (instance) => { await instance.render(); }
};
  setTimeout(function(){
    const t=document.createElement('script');
    t.src="https://web-chat.global.assistant.watson.appdomain.cloud/versions/" + (window.watsonAssistantChatOptions.clientVersion || 'latest') + "/WatsonAssistantChatEntry.js";
    document.head.appendChild(t);
  });
</script>
<body></body>

</html>
