---
template: main.html
---

<img src="https://raw.githubusercontent.com/ExpressLRS/ExpressLRS-Hardware/master/img/software.png">

## Loan Model

!!! note "Scenario"
    You are flying with your buddies and your friend has crashed all his models. You'd like to be able to lend him one of yours but you
    can't because it's using a binding phrase, so he's relegated to being the crashed model fetcher for the rest of the day!

    No longer is he destined to be running to the bando and back again fetching downed quads. You can use the "Loan Model" feature and lend him one of your models!

## How to "Loan Model"

### On the lenders handset

1. Connect to the model you wish to loan out with your handset
2. Enter the LUA screen and select "Other Devices" at the bottom of the list

    ![Other Devices](../assets/images/loan-other-devices.png)

3. Choose the RX from the list

    ![Select RX](../assets/images/loan-rx-select.png)

4. Select the "Loan Model" entry

    ![Loan Model](../assets/images/loan-rx-menu.png)

5. The receiver LED should go into the bind flashing state

    ![LEDSEQ_BINDING](https://cdn.discordapp.com/attachments/738450139693449258/921065812763218010/LEDSEQ_BINDING_10_10_10_100.gif)

### On the borrowers handset
1. From the main ExpressLRS LUA screen select `[Bind]`
2. The receiver LED should turn solid on, and the handset should connect to the recevier
    ![CONNECTED](https://cdn.discordapp.com/attachments/738450139693449258/921065812507373568/LED_ON.gif)

## Returning a "Loaned" Model

There are a couple of ways to return a model to the owner. 

The first method is for the borrower to return it from the LUA script as follows:

  1. On the borrowers handset, connect to the "loaned" model
  2. Enter the LUA screen and select "Other Devices" at the bottom of the list

      ![Other Devices](../assets/images/loan-other-devices.png)

  3. Choose the RX from the list

      ![Select RX](../assets/images/loan-rx-select.png)

  4. Select the "Return Model" entry

      ![Return Model](../assets/images/loan-return.png)

The second method used if the borrower forgets to return the model, is as follows:

  1. Power cycle the model 3 times in rapid succession, turning it off each time after the LED flashes on and off again.
  2. If done correctly, the model will return to the state where it is bound to your transmitter.

!!! note
    If the LED returns to normal flashing between reboots, the counter is reset to 0 and you must restart the process.


## Bump to Loan

On transmitter modules with an accelerometer (such as the Axis Thor), you can loan and return a model by bumping it to another transmitter. 

The process is easy - simply hold both the lender and the borrower's transmitters vertically while a model is connected and not armed and bump them together. 

!!! note
    If the borrower does not have an accelerometer, the borrower must go into binding mode manually. 

