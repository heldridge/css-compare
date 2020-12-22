---
name: Semantic UI
stylesheetSource: <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/semantic-ui@2.4.2/dist/semantic.min.css">
jsSource: |
  <script src="https://code.jquery.com/jquery-3.1.1.min.js" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/semantic-ui@2.4.2/dist/semantic.min.js"></script>
button: ui button
buttonDefault: ui primary
buttonAlternate: basic
buttonDisabled: disabled
divider: ui section divider
header: ui header
do_subheader: true
subheader: sub header
form: "ui form"
input-block: ui labeled input
input: ""
label: ui label
select: ui fluid dropdown
radio-block: ui radio checkbox
radio-input: ""
radio-label: ""
checkbox-block: "ui checkbox"
checkbox: ""
checkbox-label: ""
textarea-block: ""
textarea: ""
badge: "ui blue label"
switch-block: ui toggle checkbox
switch-input: ""
switch-label: ""
table: ui celled table unstackable
message: ui message
extraJS: |
  $('select.dropdown').dropdown();
  $('.ui.radio.checkbox').checkbox();
  $('.ui.checkbox').checkbox();
---
