---
title: Radio button
codename: JBRadioButton
category: Controls
---

Radio buttons is used to choose only one option from several mutually exclusive options.
![]({{site.baseurl}}/images/radiobutton/radio_example.png)
## When to use
Use the radio button to choose only one parameter from 2—4 options.

Do **not** use radio buttons in the following cases:
* If the user might select multiple options, use a [Checkbox]({{site.baseurl}}/controls/checkbox).
* If there are only two opposite options such as Yes and No, instead use a checkbox:
  <table>
  <col width="200px">
      <tr>
          <td> <p class="label incorrect">Incorrect</p> </td>
          <td> <p class="label correct">Correct</p> </td>
      </tr>
      <tr>
          <td> <img src="{{site.baseurl}}/images/radiobutton/tworadio_incorrect.png" style="margin-top: -5px; margin-bottom: 5px;"> </td>
          <td> <img src="{{site.baseurl}}/images/radiobutton/tworadio_correct.png" style="margin-top: -5px; margin-bottom: 5px;"> </td>
      </tr>
  </table>
* If the parameter list includes more than 4 number choices with equal steps between, use the slider to select from a number range. Also if the specific value does not matter (e.g. delay in milliseconds) or it’s possible to provide feedback on the effect of the setting changes.


Consider using a [Dropdown]({{site.baseurl}}/controls/dropdown):
* If the number of options is more than four:
  <table>
  <col width="200px">
      <tr>
          <td> <p class="label incorrect">Incorrect</p> </td>
          <td> <p class="label correct">Correct</p> </td>
      </tr>
      <tr>
          <td> <img src="{{site.baseurl}}/images/radiobutton/dropdown_incorrect.png" style="margin-top: -5px; margin-bottom: 5px;"> </td>
          <td> <img src="{{site.baseurl}}/images/radiobutton/dropdown_correct.png" style="margin-top: -5px; margin-bottom: 5px;"> </td>
      </tr>
  </table>
* If the screen space is limited.
* If it is assumed that the option will be changed less often than others on the screen.
* If there are other dropdowns on the window. The list of radio buttons is more noticeable than the dropdown, so they will look like more important settings.
* If layout combines various UI elements for one setting. In this case a dropdown can be used for options even if their number is less than four:
    ![]({{site.baseurl}}/images/radiobutton/dropdown.png)
*The automatic updates setting consists of a checkbox, three lengthy-labeled options in a dropdown and a button.*

## How to use

### Label
* Place a label after each radio button:
    ![]({{site.baseurl}}/images/radiobutton/label.png)
* A labels should be short and intelligible. Write the label as a phrase with no ending punctuation.
* Use sentence-style capitalization.
* If a label is long, move a part of the label to the second line and align the radio button with the first line of the label.If the label is too long, [shorten it]({{site.baseurl}}/text/writing_short). Do not write labels over more than two lines:
    ![]({{site.baseurl}}/images/radiobutton/twoline_label.png)
* A label describes the selected state of the radio button. Radio button is the answer “yes”, do not use negation in labels:
    <p class="label incorrect">Incorrect</p>
    ![]({{site.baseurl}}/images/radiobutton/answeryes_incorrect.png)

    <p class="label correct">Correct</p>
    ![]({{site.baseurl}}/images/radiobutton/answeryes_correct.png)
* Remove verbs that explain the function of radio button.
  Verbs such as "prefer" are extra because they are already expressed by radio button. Selection of a radio button means its option is preferred:
    <p class="label incorrect">Incorrect</p>
    ![]({{site.baseurl}}/images/radiobutton/prefer_incorrect.png)

    <p class="label correct">Correct</p>
    ![]({{site.baseurl}}/images/radiobutton/prefer_correct.png)
* Remove duplicate words at the beginning of labels as described in [recommendation for writing]({{site.baseurl}}/text/writing_short). The repeating part of the sentence can be used in the group header.

### Group label
A group of radio buttons always has a group label or a parent control with label, which explains what the options are for. A checkbox or a radio button with description of the group in the label can be a group label. Label always ends with a colon:
    ![]({{site.baseurl}}/images/radiobutton/grouplabel.png)

**Placement**
* Usually radio buttons are arranged vertically and left-aligned:
    ![]({{site.baseurl}}/images/radiobutton/placementvertically.png)
* If there are space constraints or the labels contain only one or two short words, the group of 2-3 radio buttons can be aligned horizontally:
    ![]({{site.baseurl}}/images/radiobutton/placementhorizontally.png)
* Align dependent elements with the label:
    ![]({{site.baseurl}}/images/radiobutton/placementalign.png)

## Style
### Colors and fonts
Label font: default.


Mac:
    ![]({{site.baseurl}}/images/radiobutton/style_mac.png)
    ![]({{site.baseurl}}/images/radiobutton/style_mac_g.png)
Darcula:
    ![]({{site.baseurl}}/images/radiobutton/style_darcula.png)
Windows:
    ![]({{site.baseurl}}/images/radiobutton/style_win.png)
### Sizes
The radio buttons have a permanent and unchangeable size, it cannot become bigger or smaller.

Mac:
    ![]({{site.baseurl}}/images/radiobutton/size_mac.png)
Darcula:
    ![]({{site.baseurl}}/images/radiobutton/size_darcula.png)
Windows:
    ![]({{site.baseurl}}/images/radiobutton/size_win.png)
### Spacing
* Label:
    ![]({{site.baseurl}}/images/radiobutton/spacing_label.png)
* Horizontal alignment with label:

Mac:
    ![]({{site.baseurl}}/images/radiobutton/spacing_horizontal_mac.png)
Darcula:
    ![]({{site.baseurl}}/images/radiobutton/spacing_horizontal_darcula.png)
Windows:
    ![]({{site.baseurl}}/images/radiobutton/spacing_horizontal_win.png)
* Two-line label:
    ![]({{site.baseurl}}/images/radiobutton/spacing_twoline.png)
* Vertical group:
    ![]({{site.baseurl}}/images/radiobutton/spacing_vertical.png)
* Horizontal group:
    ![]({{site.baseurl}}/images/radiobutton/spacing_horizontal_group.png)





