| Title | Key Pathfinder |
| :-- | :---|
|Author |Sadrita Neogi|




### About
A small basic strategy machine using only 4 buttons and 4 leds. It uses a Seeed Studios Xiao RP2040 for logic it is also use to control the keyboard shortcuts.

### Why I chose this project?
Behind choosing this project, when I have started stasis I was not sure about what I can. Then. I see the starter project where I find this pathfinder that to be built, so I make it with some extra features like in the starter project, it has only three keys, so I added one extra keys just to use the more functionality of the device, so I have build this project.

### How to use this project
This project can be used in multiple waste based upon the user need best for me. I will use it for the shortcut that I have implemented and also it also works as a stress reliever. When I am bored, I can place the key and the LED will blink, according to the input that I am giving.



<div align="center">

| | PCB Designing | |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/6cfc5252-5915-4c42-8057-84c6e82beba6" width="250" alt="PCB Design 1" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/47c79d92-18f0-4dce-ac68-c5a9cd02457a" width="250" alt="PCB Design 2" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/5f385ca5-4691-4acf-a2cf-5f1001ea63ff" width="250" alt="PCB Design 3" style="border-radius: 12px;" /> |
| <img src="https://github.com/user-attachments/assets/a6298b81-fcdf-43fb-a627-6b458d0fbdaf" width="250" alt="PCB Design 4" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/d40cefee-8d61-495d-a6a5-004729eff86e" width="250" alt="PCB Design 5" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/0751569a-2af2-4997-9da3-a0ecf81d6242" width="250" alt="PCB Design 6" style="border-radius: 12px;" /> |
| <img src="https://github.com/user-attachments/assets/718a5b27-1fe6-4fba-a875-b19e9574b4f3" width="250" alt="PCB Design 7" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/c14df95b-8b6b-4b06-9b0a-eb8dbd064b12" width="250" alt="PCB Design 8" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/420cc67c-6467-4121-baea-179a85defb86" width="250" alt="PCB Design 9" style="border-radius: 12px;" /> |

  
<!-- TWO-COLUMN IMAGE FRAME GRID -->
<div align="center">
  <table border="0" cellpadding="10" cellspacing="0" style="border-collapse: collapse;">
    <tr>
      <!-- FRONT SIDE CARD -->
      <td align="center" valign="top" width="50%" style="background: #ffffff; border: 1px solid #d0d7de; border-radius: 12px; padding: 16px; box-shadow: 0 4px 12px rgba(0,0,0,0.05);">
        <img src="https://github.com/user-attachments/assets/51b06ebd-5026-44ca-a4ad-e85688aaa20f" width="100%" alt="Front Side View" style="border-radius: 6px;" />
        <div style="margin-top: 12px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size: 13px; color: #57606a; font-weight: 600; text-transform: uppercase; letter-spacing: 0.5px;">
          ▲ Front Side View
        </div>
      </td>
      <!-- SPACER FOR GITHUB MOBILE DEGRADATION -->
      <td width="2%">&nbsp;</td>
      <!-- BACK SIDE CARD -->
      <td align="center" valign="top" width="50%" style="background: #ffffff; border: 1px solid #d0d7de; border-radius: 12px; padding: 16px; box-shadow: 0 4px 12px rgba(0,0,0,0.05);">
        <img src="https://github.com/user-attachments/assets/1fa94b5b-e2d9-4074-b4df-c563920f1178" width="100%" alt="Back Side View" style="border-radius: 6px;" />
        <div style="margin-top: 12px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size: 13px; color: #57606a; font-weight: 600; text-transform: uppercase; letter-spacing: 0.5px;">
          ▲ Back Side View
        </div>
      </td>
    </tr>
  </table>
</div>
</div>


<div align="center">
  <h2> Bill of Materials </h2>
</div>

| Component Name | Purpose | Qty | Unit Price | Total Price in USD | Link |
| :--- | :--- | :---: | :---: | :---: | :---: |
| **Resistors(220 Ohm 0.25W )** | To control the current flow | 4 | $0.0096 | $0.04 | [Link](https://robu.in/product/220-ohm-resistor-0-25w-metal-film-pack-of-100/?gad_source=1&gad_campaignid=17427802703&gbraid=0AAAAADvLFWekTwWN9jC03A8IQT8r3AlY5&gclid=CjwKCAjw6f3RBhApEiwAMaCqWcaO2dly3_fFTVA-yL3R27B3th02OcCqODYx5UqYKDzOy5vnEFLU-hoCv24QAvD_BwE) |
| **3mm Green DIP LED** | For the light | 4 | $0.016 | $0.6 | [Link](https://robu.in/product/5mm-green-surface-mount-led-pack-of-50/?gad_source=1&gad_campaignid=17427802703&gbraid=0AAAAADvLFWekTwWN9jC03A8IQT8r3AlY5&gclid=CjwKCAjw6f3RBhApEiwAMaCqWRUCdY8CmAQTw0-cabIrtaeX7ebfmDpTQ9LgE_gcqU91_RtSVQTk3hoCW7cQAvD_BwE)|
| **Blank Keycaps (10)** | To put it in the switches | 1 | $1.59 | $1.59 | [Link](https://stackskb.com/store/numpad-keycaps/) |
| **Seeed Studio XIAO RP2040** | To control the board | 1 | $6.55 | $6.55 | [Link](https://robu.in/product/seeed-studio-xiao-rp2040-v1-0/) |
| **PCB Board** | The main board | 1 | $2.00 | $2.00 | [Link](https://jlcpcb.com/) |
| **Linear Switch (moq 10)** | To press the switch | 1 | $3.18 | $3.18 | [Link](https://stackskb.com/store/hmx-switch-tester/) |


<div align="center">
  <table border="0" cellpadding="0" cellspacing="0" style="border-collapse: collapse; max-width: 600px;">
    <tr>
      <td style="background: #ffffff; border: 1px solid #d0d7de; border-radius: 12px; padding: 20px; box-shadow: 0 4px 12px rgba(0,0,0,0.05); font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">
        <div style="font-size: 16px; font-weight: 600; color: #24292f; margin-bottom: 12px; border-bottom: 1px solid #d0d7de; padding-bottom: 8px;">
           Final Summary Title
        </div>
        <table width="100%" border="0" style="border-collapse: collapse; font-size: 14px; color: #57606a;">
          <tr>
            <td style="padding: 4px 0;">Component Subtotal:</td>
            <td align="right" style="font-weight: 500; color: #24292f;">$13.42</td>
          </tr>
          <tr>
            <td style="padding: 4px 0;">Shipping Cost(incl. PCB):</td>
            <td align="right" style="font-weight: 500; color: #24292f;">$11</td>
          </tr>
          <tr>
            <td style="padding: 4px 0; padding-bottom: 8px;">Tax:</td>
            <td align="right" style="font-weight: 500; color: #24292f;">$0.5</td>
          </tr>
          <tr style="border-top: 1px dashed #d0d7de;">
            <td style="padding: 12px 0 0 0; font-weight: 600; color: #24292f; font-size: 15px;">Net Total Cost:</td>
            <td align="right" style="padding: 12px 0 0 0; font-weight: bold; color: #2da44e; font-size: 18px;">$24.92</td>
          </tr>
          <tr>
            <td style="padding: 2px 0 0 0; font-size: 11px; color: #8c959f;">Projected Budget Allocation:</td>
            <td align="right" style="padding: 2px 0 0 0; font-weight: 500; font-size: 12px; color: #8c959f;">$25</td>
          </tr>
        </table>
      </td>
    </tr>
  </table>
</div>

---

**Project Under Hack Club**
