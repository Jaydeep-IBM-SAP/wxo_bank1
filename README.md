<!DOCTYPE html>
<html lang="en-US">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>New Watson Assistant Bank</title>
</head>
<body>
    <img src="DTE_Bank_wxO.png" alt="New Watson Assistant Bank" style="max-width:100%; height:auto;" />
    <script>
      window.watsonAssistantChatOptions = {
        integrationID: "cde39977-5eca-4ca5-a371-eca64341ff06",
        region: "aws-us-east-1",
        serviceInstanceID: "20250701-1627-3065-109e-0d7c2d324439",
        orchestrateUIAgentExtensions: false,
        onLoad: async (instance) => { await instance.render(); }
      };
      setTimeout(function(){
        const t=document.createElement('script');
        t.src="https://web-chat.global.assistant.watson.appdomain.cloud/versions/" + (window.watsonAssistantChatOptions.clientVersion || 'latest') + "/WatsonAssistantChatEntry.js";
        document.head.appendChild(t);
      });
    </script>
</body>
</html>
