## IFTTT Web SetUp
After setting up an account for IFTTT, follow the steps below.
1) Go to "Create" <br/> <img src="https://user-images.githubusercontent.com/56757186/109113658-8b7d7280-7777-11eb-980f-6863fb197c62.jpg">
2) Click "If This" <br/> <img src="https://user-images.githubusercontent.com/56757186/110071077-58119800-7db6-11eb-8e3c-a185b88c86b5.png">
3) Search "Webhook" <br/> <img src="https://user-images.githubusercontent.com/56757186/110071284-b9396b80-7db6-11eb-9187-5b28fb7b4239.png">
4) Choose "Receive Web Request" <br/> <img src="https://user-images.githubusercontent.com/56757186/110071532-2b11b500-7db7-11eb-9cd4-1bea8e4e6e33.png">
5) Type in the event name of your choice. In this example, we will use "temperature"<br/>
6) Click "Create Trigger" <br/> <img src="https://user-images.githubusercontent.com/56757186/110071781-9fe4ef00-7db7-11eb-8f4e-b3822f45f12d.png">
7) Click "Then That" <br/> <img src="https://user-images.githubusercontent.com/56757186/110080383-53081500-7dc5-11eb-803f-35c73ae12aa6.png">
8) Search "Notifications" <br/> <img src="https://user-images.githubusercontent.com/56757186/110080580-9ebabe80-7dc5-11eb-90c0-b93748ee3b03.png">
9) Choose "Send a notification from the IFTTT app" <br/> <img src="https://user-images.githubusercontent.com/56757186/110080809-f9541a80-7dc5-11eb-9c0a-156338514e60.png">
10) In "Eventname", change it to any event name of your choice. In this tutorial, we will change it to "temperature".<br/>
  Note: Remember to remove the curly brackets {}, i.e. Change {EventName} to {temperature}, or your choice of name. <br/> <img src="https://user-images.githubusercontent.com/56757186/110081287-ac247880-7dc6-11eb-8a13-d360bdc8cbdb.png">
11) Press "Create Action"  <br/> <img src="https://user-images.githubusercontent.com/56757186/110081777-65834e00-7dc7-11eb-8ba1-0fc13288480a.png">
12) Your page should look like this. Press "Continue" <br/> <img src="https://user-images.githubusercontent.com/56757186/110081877-8e0b4800-7dc7-11eb-85eb-212f61031d58.png">
13) Press "Finish" <br/> <img src="https://user-images.githubusercontent.com/56757186/110081925-a11e1800-7dc7-11eb-82d5-6fc7123643f2.png">
14) The IFTTT web configuration is all setup! Now we need the IFTTT app on your phone. Go to the App Store/Google Play (depending on your phone) and search "IFTTT". Install it.
 <br/> <img src="https://user-images.githubusercontent.com/56757186/110082559-76808f00-7dc8-11eb-8d34-5ee1657f7c55.jpg">
15) Click on the webhook icon, as shown belown. <br/> <img src="https://user-images.githubusercontent.com/56757186/110082830-d9722600-7dc8-11eb-8dee-8ef8aa10adae.jpg">
16) Click on "Documentation" <br/> <img src="https://user-images.githubusercontent.com/56757186/110083123-44bbf800-7dc9-11eb-899a-6a5b475d0c1a.jpg">
17) Your key is created! Each key created is unique. I have covered mine in the yellow area due to confidentiality. In the blue highlighted area, change "{event}" to "temperature".<br/>
18) Copy this part:"https://<span></span>maker.ifttt.com/trigger/temperature/with/key/{yourkey}". We will be using this key later. <br/> <img src="https://user-images.githubusercontent.com/56757186/110084483-f90a4e00-7dca-11eb-8f00-33427fe4d8d8.jpg">
