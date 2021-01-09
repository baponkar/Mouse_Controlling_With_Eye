# Mouse Controll With Eye

![Python3](https://img.shields.io/badge/Python-3-green)
![OpenCV2](https://img.shields.io/badge/Open-CV2-yellow)
![Pyautogui](https://img.shields.io/badge/Pyauto-Gui-yellowgreen)
[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](<div id="smart-button-container">
      <div style="text-align: center;">
        <div id="paypal-button-container"></div>
      </div>
    </div>
  <script src="https://www.paypal.com/sdk/js?client-id=sb&currency=USD" data-sdk-integration-source="button-factory"></script>
  <script>
    function initPayPalButton() {
      paypal.Buttons({
        style: {
          shape: 'rect',
          color: 'gold',
          layout: 'vertical',
          label: 'paypal',
          
        },

        createOrder: function(data, actions) {
          return actions.order.create({
            purchase_units: [{"amount":{"currency_code":"USD","value":1}}]
          });
        },

        onApprove: function(data, actions) {
          return actions.order.capture().then(function(details) {
            alert('Transaction completed by ' + details.payer.name.given_name + '!');
          });
        },

        onError: function(err) {
          console.log(err);
        }
      }).render('#paypal-button-container');
    }
    initPayPalButton();
  </script>)

* :octocat: Version -v-1.0.0
* :octocat: License- GNU GPL V3.O

## DESCRIPTION:
* This Python🐍 Script helps to move a mouse cursor by using eye.
* This script just move the cursor➡️ not to click by eye👁 blink. 
* You can help me to add that feature.
* To access the feature you must have a webcam🎦 in your computer💻.

* The following Python library Modules required [openCV](https://pypi.org/project/opencv-python/) and [pyautogui](https://pypi.org/project/PyAutoGUI/) :
* You can download those by this pip commands.

```
$  pip install cv2
```
```
$  pip install pyautogui
```

See this [▶️Youtube](https://youtu.be/S0y8dxwbJzY) ![Screenshot](Screenshot_20200928-000225_YouTube.jpg)(https://youtu.be/S0y8dxwbJzY)   link to see the demo Video.

* I will appreciate :+1: any kind suggestions and help.
