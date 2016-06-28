# Harsha1
# Harsha 2
# Harsha 3
# Harsha 4

efd.get(CONFIG.getProperty("testsitename"));
		getelement("Register_link").click();
		Thread.sleep(2000l);
		getelement("Email_Input").sendKeys(email);
		getelement("Name_Input").sendKeys(name); 
		getelement("Password_password").sendKeys(password);
		getelement("reconfirm_password").sendKeys(confirmpassword);
		getelement("Register_Button").click(); 
		Thread.sleep(2000l);
		
		try
