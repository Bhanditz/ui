---
title: Checkbox
category: Controls
order: 4
---

A checkbox describes a state or action that can be either on or off.
<br/> The marked checkbox corresponds to the answer "yes"
<br/>
  ![]( {{ site.baseurl }}/images/checkbox/one_checkbox.png)


Checkboxes are used for selecting:
* objects,
* attributes or states,
* modifications of default behavior (settings).

Use checkbox for:
* Select stand alone object or several objects from group. Use [radio button]( {{ site.baseurl }}/controls/radiobutton/) if only one option from the list can be selected.
* Yes/no choice which does not lead to immediate action. Use Toggle to initiation immediate action.

## Guidelines
* A checkbox toggles between two states that are completely opposite as "on/off". If two states of a setting are not completely opposite, use two radio buttons and label them accordingly.
<br />
![]( {{ site.baseurl }}/images/checkbox/two_radiobuttons.png)
* A group of checkboxes may not have a common label or header though it is advisable to add one. The group header makes finding a necessary setting faster.
<br />
![]( {{ site.baseurl }}/images/checkbox/checkbox_header.png)
* Checkboxes can also be grouped just by extra vertical space. First items in each group define group contents and help finding a group of settings faster, similar to group headers.
<br />
![]( {{ site.baseurl }}/images/checkbox/vertical_space.png)
* The group of 2-3 checkboxes can be aligned horizontally.
<br />
![]( {{ site.baseurl }}/images/checkbox/checkbox_horizontally.png)
* Clicking on body of mark selects/removes checkbox.
* When options can be grouped, you can use an indeterminate checkbox to represent the whole group. Use indeterminate state check box when a user selects some, but not all, sub-items in the group.
<br />
![]( {{ site.baseurl }}/images/checkbox/checkbox_indeterminate.png)
* Use indentation to show hierarchy within a group.
<br />
![]( {{ site.baseurl }}/images/checkbox/checkbox_hierarchy.png)
* Labels
    * Checkbox is the answer "yes", so do not use negation in labels.
    * Use sentence-style capitalization.
    * Learn recommendations for [UI text]( {{ site.baseurl }}/principles/ui_text/).

## Alignment with other elements
* An independent checkbox is left-aligned with elements above and below it:
![]( {{ site.baseurl }}/images/checkbox/alignment_left.png)
* When a checkbox depends on an element it follows, the following alignments are possible:
   * If a preceding input element has a short label, left-align the checkbox with the element.
   <br /> ![]( {{ site.baseurl }}/images/checkbox/alignment_depends.png)
   * If the label is long or the element itself is narrow, use an indent that equals the width of the checkbox itself plus the distance between the checkbox and its label.
   <br /> ![]( {{ site.baseurl }}/images/checkbox/alignment_longlabel.png)
   * If a checkbox label is short, the checkbox can be placed into the same line with an element.
   <br /> ![]( {{ site.baseurl }}/images/checkbox/alignment_checkboxlabel.png)
   * If an element depends on a checkbox or a radio button, left-align the element with the checkboxes' or radio's label.
   <br /> ![]( {{ site.baseurl }}/images/checkbox/alignment_checkboxdepends.png)
   <br />The checkbox, the text field and the button depend on the top radio button and are all aligned with the radio’s label.
   * At the bottom of a dialog, a checkbox can be aligned with buttons.
   <br /> ![]( {{ site.baseurl }}/images/checkbox/alignment_buttons.png)

## Mac OS default
<br /> ![]( {{ site.baseurl }}/images/checkbox/mac_os_checkbox.png)

## Darcula 
![]( {{ site.baseurl }}/images/checkbox/darcula_checkbox.png)

## Windows 10

![]( {{ site.baseurl }}/images/checkbox/win_checkbox.png)
