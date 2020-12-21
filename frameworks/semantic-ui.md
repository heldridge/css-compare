---
name: Semantic UI
stylesheetSource: <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/semantic-ui@2.4.2/dist/semantic.min.css">
jsSource: |
    <script src="https://code.jquery.com/jquery-3.1.1.min.js" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/semantic-ui@2.4.2/dist/semantic.min.js"></script>
buttonClass: ui button
buttonDefault: ui primary
buttonAlternate: basic
buttonDisabled: disabled
divider: ui section divider
headerClass: ui header
input-block: ui labeled input
input: ""
label: ui label
select: ui fluid dropdown
radio-block: ui radio checkbox
radio-input: ""
radio-label: ""
extraJS: |
    $('select.dropdown').dropdown();
    $('.ui.radio.checkbox').checkbox();
---