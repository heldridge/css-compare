---
name: Materialize
stylesheetSource: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">
jsSource: |
    <script src="https://code.jquery.com/jquery-3.1.1.min.js" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
buttonClass: " "
buttonDefault: waves-effect waves-light btn
buttonPrimary: waves-effect waves-light btn
buttonAlternate: waves-effect waves-teal btn-flat
buttonDisabled: btn disabled
divider: ""
headerClass: ""
do_subheader: false

form: ""
input-block: input-field
input: ""
label: ""
select: ""
checkbox: ""
textarea-block: "input-field"
textarea: "materialize-textarea"
badge: new badge
extraJS: |
    $(document).ready(function(){
        $('select').formSelect();
    });
---