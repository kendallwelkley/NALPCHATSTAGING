<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
window.addEventListener("onEmbeddedMessagingReady", e => {
						  embeddedservice_bootstrap.prechatAPI.setVisiblePrechatFields({
						    // List the pre-chat field names with the value and whether
						    // it's editable in the pre-chat form.
		 						"_email": {
						      	"value": "kwelkle11@gmail.com",
						      	"isEditableByEndUser": false
						    	},
							 	"Account_Code": {
						      	"value": "KW456",
						      	"isEditableByEndUser": false
								},
								"_firstName": {
						      	"value": "Kendall",
						      	"isEditableByEndUser": true
						    	},
		 						"_lastName": {
						      	"value": "Welkley",
						      	"isEditableByEndUser": true
						    	},
		 				  });
                          
						});
			embeddedservice_bootstrap.init(
				'00DP0000003zzZf',
				'Customer_Support_1',
				'https://fleetcorna--stagingdev.sandbox.my.site.com/ESWCustomerSupport1758657276991',
				{
					scrt2URL: 'https://fleetcorna--stagingdev.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://fleetcorna--stagingdev.sandbox.my.site.com/ESWCustomerSupport1758657276991/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
