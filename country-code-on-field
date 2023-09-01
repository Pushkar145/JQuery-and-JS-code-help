jQuery(function() {
  jQuery('#iti-0__country-listbox').change(function() {
    var countryCode = jQuery(this).find('li:selected').data('dial-code');
    var value = '+' + jQuery(this).val();
    jQuery('input.wpforms-smart-phone-field').val(value).intlTelInput('setCountry', countryCode);
  });
  var code = '+971';
	jQuery('.iti__flag').addClass('iti__ae');
    jQuery('input.wpforms-smart-phone-field').val(code).intlTelInput();
	
});
