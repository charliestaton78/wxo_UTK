<html lang="en-US">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <img src = "UTK_wxO.png"
    	width="auto" height="1200"
         alt = "New Watson Assistant UTK" />

</head>

<script>
  window.wxOConfiguration = {
    orchestrationID: "20250430-1552-4383-00f2-8e9318aa2f1b_20250501-1814-2773-9095-04757cf91ef5",
    hostURL: "https://dl.watson-orchestrate.ibm.com",
    rootElementID: "root",
    chatOptions: {
        agentId: "bb30d23d-dfbd-44bb-8818-ff387648ac97", 
        agentEnvironmentId: "96f7ead6-d68e-4665-bf6a-aae227f29902",
    }
  };
  setTimeout(function () {
    const script = document.createElement('script');
    script.src = `${window.wxOConfiguration.hostURL}/wxochat/wxoLoader.js?embed=true`;
    script.addEventListener('load', function () {
        wxoLoader.init();
    });
    document.head.appendChild(script);
  }, 0);                     
</script>
<body></body>

</html>
