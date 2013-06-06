Iconpack
========

Iconpack Template
Unzip project and navigate to Template>Icon Pack Template>MainActivity>res and update:
  
	Update with your icons, wallpapers and theme preview in drawable-nodpi if necessary
	Import your icons into the drawable-hdpi



1. Import Project into Eclipse

2. Navigate to >Template>src>com.yourname.youriconpackname
  \nRight-click on package name
	Select Refactor and Rename

3. Expand 'com.yourname.youriconpackname'
	Open MainActivity.java and make the necessary changes

		Line 77 = E-mail
		Line 93 = XDA URL
		Line 106 = Google Plus URL
		Line 120 = Website URL
	Open rateplay.java and make the necessary changes:
  
		Line 50 = Google Play Link
		Line 63 = Rate App (App Link)
		Line 75 = Donate (Paypal Link)
	Save both activites and close 

4. Navigate to Template>res>values and open strings.xml
	Change the following strings:

		theme_title
		developer_name
		developer_link
		theme_description
		aboutdev
	Save and close strings.xml

5. Navigate the following and update per your icons:

	Template>res>values>icon_pack.xml
	Template>res>xml>appfilter.xml
	Template>res>xml>drawable.xml

6. Open AndroidManifest.xml and change the following:	

	Package = change to com.yourname.youriconpackname
	Version Code = Increase by one each time your wish to upload to Playstore, otherwise leave as is.


