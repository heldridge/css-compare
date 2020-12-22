---
name: Materialize
stylesheetSource: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">
jsSource: |
  <script src="https://code.jquery.com/jquery-3.1.1.min.js" crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
buttonClass: " "
buttonDefault: waves-effect waves-light btn
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
radio-block: ""
radio-input: ""
radio-label: ""
checkbox-block: ""
checkbox: ""
checkbox-label: ""
textarea-block: "input-field"
textarea: "materialize-textarea"
blockquote: ""
badge: new badge
switch_html: |
  <p>Switch</p>
  <div class="switch">
      <label>
      Off
      <input type="checkbox">
      <span class="lever"></span>
      On
      </label>
  </div>
table: ""
extraJS: |
  $(document).ready(function(){
      $('select').formSelect();
  });
---
