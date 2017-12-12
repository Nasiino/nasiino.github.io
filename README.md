# nasiino.github.io
Before: </div><h2 style=”text-allign:center;”><u>Resource Finder</u></h2> 
<p> This interactive decision tree will help you find the program or service you are looking for by answering a series of questions. Participating in a service or program can help you get and stay on track. When the court sees progress, they are more willing to work with you. This resource finder will help clients, lawyers, social workers, and anyone interested in bettering their lives through the use of social programs and services. This list was complied with the help of social workers and lawyers. </p>

<style>	
	body {
		font-family: 'Palatino Linotype', 'Book Antiqua', Palatino, serif;
	}

	#rawmarkup{
		display:none;
	}
	
	#QandA img{
		width:100%;
	}

	div.main{
		min-width:300px;
		max-width:650px;
		margin: 0 auto;
	padding:0 5px 0 5px;
		}
	div.frame{
		float:left;
		width:100%;
		margin:5px 0 5px 0;
	}
	div.full{
		float:left;
		width:100%;
	}
	.button{
		padding:8px;
		margin:8px 0 0px 0;
		width:100%;
	}
	div.question_text{
		float:left;
		font-family: Verdana, Geneva, sans-serif;
		font-size: 14px;
		line-height: 20px;
		color:#ffffff;
		min-width:30px;
		background:#5489eb;
		border-radius: 15px;
		padding:10px 15px 14px 15px;
		margin-right:45px;
	}

	div.question_text a:link, div.question_text a:hover, div.question_text a:active, div.question_text a:visited{ color:#e3fbfc; } 

	div.question_arrow{
		float:left; 
		width: 0; 
		height: 0; 
		border-left: 5px solid transparent; 
		border-right: 10px solid transparent; 
		border-top: 15px solid #5489eb;
		margin:0 20px;
	}
	div.ans_text{
		float:right;
		font-family: Verdana, Geneva, sans-serif;
		font-size: 14px;
		line-height: 20px;
		color:#000000;
		min-width:30px;
		background:#eeeeee;
		border-radius: 15px;
		padding:10px 15px 14px 15px;
		margin-left:45px;
	}
	div.ans_arrow{
		float:right; 
		width: 0; 
		height: 0; 
		border-left: 10px solid transparent; 
		border-right: 5px solid transparent; 
		border-top: 15px solid #eeeeee;
		margin:0 20px;
	}
	div.choices{
		float:left;
		width:100%;
		margin:15px 0 0 0;
	}
	div.standard_buttons{
		float:left;
		width:100%;
		margin-top:5px;
		border-top: 1px solid #ddd; 
		padding-top:12px;		
	}
	div.credits{
		float:left;
		dispaly:none;
		width:100%;
		background:#eee;
		margin:0px 0 15px 0;
	}
	div.credit_text{
		font-family: Verdana, Geneva, sans-serif;
		font-size: 14px;
		line-height: 20px;
		padding:4px 15px 10px 15px;
	}
	li.error{
		list-style-type: none;
		background:#ffdddd;
		margin: 10px 0 0 0;
		padding: 5px;
	}

	.qpad {
		float:left;
		padding:0 15px;
	}
	
	a.sbutton {
		float:left;
		font-family: Verdana, Geneva, sans-serif;
		font-size: 14px;
		line-height: 20px;
		width:48%;
		background: #eee;
		border-radius: 8px;
		padding:10px 0px 12px 0;
		margin: 0 0 3px 0;
		border: solid 1px #888;
		text-align:center;
		color: #000000;
		text-decoration: none;
	}

	a.sbutton:hover, a.sbutton:active {
		float:left;
		font-family: Verdana, Geneva, sans-serif;
		font-size: 14px;
		line-height: 20px;
		width:48%;
		background: #ddd;
		border-radius: 8px;
		padding:10px 0px 12px 0;
		margin: 0 0 3px 0;
		border: solid 1px #888;
		text-align:center;
		color: #000000;
		text-decoration: none;
	}

	a.qabutton {
		float:left;
		font-family: Verdana, Geneva, sans-serif;
		font-size: 14px;
		line-height: 20px;
		width:100%;
		background: #eee;
		border-radius: 8px;
		padding:10px 0px 12px 0;
		margin: 0 0 8px 0;
		border: solid 1px #888;
		text-align:left;
		color: #000000;
		text-decoration: none;
	}

	a.qabutton:hover, a.qabutton:active {
		float:left;
		font-family: Verdana, Geneva, sans-serif;
		font-size: 14px;
		line-height: 20px;
		width:100%;
		background: #ddd;
		border-radius: 8px;
		padding:10px 0px 12px 0;
		margin: 0 0 8px 0;
		border: solid 1px #888;
		text-align:left;
		color: #000000;
		text-decoration: none;
	}
	

	div.xdiv {
		float:left;
		width:100%;
		margin: 0 0 8px 0;
		background: #eee;
		border: solid 1px #888;
		border-radius: 8px;
	}	

	input.xinput {
		-webkit-box-sizing: border-box; /* Safari/Chrome, other WebKit */
		-moz-box-sizing: border-box;    /* Firefox, other Gecko */ 
		box-sizing: border-box;         /* Opera/IE 8+ */
		float:left;
		width:100%;
		font-family: Verdana, Geneva, sans-serif;
		font-size: 14px;
		line-height: 20px;
		background: #fff;
		border-top-left-radius: 8px;
		border-top-right-radius: 8px;
		padding:10px 10px 12px 10px;
		border: solid 0px #888;
		border-bottom: solid 1px #888;
		text-align:left;
		color: #000000;
		text-decoration: none;
	}
	
	a.xbutton {
		float:left;
		width:100%;
		text-align:left;
		font-family: Verdana, Geneva, sans-serif;
		font-size: 14px;
		line-height: 20px;
		background: #eee;
		border-radius: 8px;
		padding:10px 0px 12px 0px;
		color: #000000;
		text-decoration: none;
	}
	
	a.xbutton:hover, a.xbutton:active {
		border-top-left-radius: 0px;
		border-top-right-radius: 0px;
		background: #ddd;
	}
</style>
<FORM name="FORM" id="FORM"><div id="conversation" style="margin:15px auto 0 auto;padding:0 15px;max-width:500px"> </div><h2 style=”text-allign:center;”><u>Resource Finder</u></h2> 
<p> This interactive decision tree will help you find the program or service you are looking for by answering a series of questions. Participating in a service or program can help you get and stay on track. When the court sees progress, they are more willing to work with you. This resource finder will help clients, lawyers, social workers, and anyone interested in bettering their lives through the use of social programs and services. This list was complied with the help of social workers and lawyers. </p>

<div id='QandA' class='QandA'><div style='padding:15px;background:#ddffdd;text-align:center;'>Loading QnA...</div></div><div id='Choices' class='choices'></div><div id="rawmarkup" style="display:none;">Before%3A+%3C%2Fdiv%3E%3Ch2+style%3D%E2%80%9Dtext-allign%3Acenter%3B%E2%80%9D%3E%3Cu%3EResource+Finder%3C%2Fu%3E%3C%2Fh2%3E+%0D%0A%3Cp%3E+This+interactive+decision+tree+will+help+you+find+the+program+or+service+you+are+looking+for+by+answering+a+series+of+questions.+Participating+in+a+service+or+program+can+help+you+get+and+stay+on+track.+When+the+court+sees+progress%2C+they+are+more+willing+to+work+with+you.+This+resource+finder+will+help+clients%2C+lawyers%2C+social+workers%2C+and+anyone+interested+in+bettering+their+lives+through+the+use+of+social+programs+and+services.+This+list+was+complied+with+the+help+of+social+workers+and+lawyers.+%3C%2Fp%3E%0D%0A%0D%0AQ%281%29%3A+Are+you+18+years+or+older%3F%0D%0AA%3A+Yes.%0D%0A%09Q%281.1%29%3A+I+will+provide+a+list+of+resources+in+the+Boston+area+that+you+can+utilize.+What+are+you+interested+in%3F%0D%0A%09A%28job+training%29%3A+Job+Training%0D%0A%09%09Q%281.1.1%29%3A+Pick+the+field+you%E2%80%99re+most+interested+in.%0D%0A%09%09A%28construction%29%3A+Construction%0D%0A%09%09%09Q%281.1.1.1%29%3A+Here+are+some+apprentice+and+training+programs+in+the+Greater+Boston+area.+%3Cbr%3E%3Cbr%3E%3Ca+href%3D%22https%3A%2F%2Fwww.peoplesacademyinc.org%22%3EThe+Peoples+Academy%3C%2Fa%3E+%3Cbr%3E%3Cbr%3E%3Ca+href%3D%22https%3A%2F%2Fbuildingpathwaysboston.org%2Fprograms%2F%22%3EBuildingPathWays%3C%2Fa%3E%3Cbr%3E%3Cbr%3E%3Ca+href%3D%22http%3A%2F%2Fwww.youthbuildboston.org%2Fnew-programs%2F%22%3EYouth+Build%3C%2Fa%3E.+%0D%0A%09%09%09A%3A+Thanks%2C+I%E2%80%99m+done+with+this.%0D%0A%09%09%09%09Q%281.1.1.1.1%29%3AGOTO%3Aend%0D%0A%09%09%09A%3A+I+want+to+keep+searching+the+resources.%0D%0A%09%09%09%09Q%281.1.1.1.2%29%3AGOTO%3A1.1%0D%0A%09%09A%28food%29%3A+Culinary+Arts%0D%0A%09%09%09Q%281.1.1.2%29%3A+%3Ca+href%3D%22https%3A%2F%2Fne-cat.org%2Fculinary-arts-job-training%2F%22%3ENECAT%3C%2Fa%3E%3Cbr%3E%3Cbr%3E%3Ca+href%3D%22http%3A%2F%2Fbostonkroc.salvationarmy.org%2FBostonKroc%2FCulinary%2F%22%3EKroc+Center+Culinary+Arts+Training+Center%3C%2Fa%3E+%0D%0A%09%09%09A%3A+Thanks%2C+I%E2%80%99m+done+with+this.%0D%0A%09%09%09%09Q%281.1.1.2.1%29%3AGOTO%3Aend%0D%0A%09%09%09A%3A+I+want+to+keep+searching+the+resources.%0D%0A%09%09%09%09Q%281.1.1.2.2%29%3AGOTO%3A1.1%0D%0A%09%09A%28unsure%29%3A+I%E2%80%99m+unsure%0D%0A%09%09%09Q%281.1.1.3%29%3A+Check+out+Boston%E2%80%99s+career+services+program+or+Boston+Public+Health+Commission%E2%80%99s+Job+Training%2FEducation%3Cbr%3E%3Cbr%3E%3Ca+href%3D%22https%3A%2F%2Fwww.bostoncareerlink.org%2Findex.php%3Foption%3Dcom_content%26view%3Darticle%26id%3D1%26Itemid%3D2%2F%22%3EBoston+Career+Link%3C%2Fa%3E%3Cbr%3E%3Cbr%3E%3Ca+href%3D%22http%3A%2F%2Fwww.bphc.org%2Fwhatwedo%2Fhomelessness%2Fhomeless-services%2FPages%2FJob-Training-and-Education.aspx%2F%22%3EBoston+Public+Health+Commission%3C%2Fa%3E%0D%0A%09%09%09A%3A+Thanks%2C+I%E2%80%99m+done+with+this.%0D%0A%09%09%09%09Q%281.1.1.3.1%29%3AGOTO%3Aend%0D%0A%09%09%09A%3A+I+want+to+keep+searching+the+resources.%0D%0A%09%09%09%09Q%281.1.1.3.2%29%3AGOTO%3A1.1%0D%0A%09A%28Alternative+education%29%3A+Alternative+Education%0D%0A%09%09Q%281.1.2%29%3A+Are+you+interested+in+getting+your+HiSET%2C+GED%2C+or+high+school+diploma%3F%0D%0A%09%09A%3A+Yes%0D%0A%09%09%09Q%281.1.2.1%29%3A+This+hotline+will+help+you+figure+the+program+that+will+benefit+you+the+most%21+%3Ca+href%3D%22http%3A%2F%2Fmassliteracyhotline.org%2Fhotline%2F%2F%22%3EMassachusetts+Literacy+Hotline%3C%2Fa%3E%0D%0A%09%09%09A%3A+Thanks%2C+I%E2%80%99m+done+with+this.%0D%0A%09%09%09%09Q%281.1.2.1.1%29%3AGOTO%3Aend%0D%0A%09%09%09A%3A+I+want+to+keep+searching+the+resources.%0D%0A%09%09%09%09Q%281.1.2.1.2%29%3AGOTO%3A1.1%0D%0A%09%09A%3A+No.%0D%0A%09%09%09Q%281.1.2.2%29%3A+Do+you+want+to+keep+searching+the+resources%3F%0D%0A%09%09%09A%3A+Yes+please%21%0D%0A%09%09%09%09Q%281.1.2.2.1%29%3AGOTO%3A1.1%0D%0A%09%09%09A%3A+No+thanks%2C+I%E2%80%99m+all+set.%0D%0A%09%09%09%09Q%281.1.2.2.2%29%3AGOTO%3Aend%0D%0A%09A%28rehab%29%3A+Rehabilitation+Facility%0D%0A%09%09Q%281.1.3%29%3A+Are+you+interested+in+participating+in+a+program+in+Boston%3F%0D%0A%09%09A%3A+Yes.%0D%0A%09%09%09Q%281.1.3.1%29%3A+Here+are+a+list+of+rehabilitation+programs+in+Boston.+%3Cbr%3E%3Cbr%3E+%3Ca+href%3D%22http%3A%2F%2Fspauldingrehab.org%2Flocations%2Fspaulding-rehabilitation-hospital%2F%22%3ESpaulding%3C%2Fa%3E%3Cbr%3E%3Cbr%3E%3Ca+href%3D%22http%3A%2F%2Fwww.bidmc.org%2FCenters-and-Departments%2FDepartments%2FPatient-And-Family-Care-Services%2FRehabilitation-Services%2FInpatient-Rehabilitation-Services.aspx%2F%22%3EBeth+Israel+Deaconess+Medical+Center%3C%2Fa%3E%3Cbr%3E%3Cbr%3E%3Ca+href%3D%22http%3A%2F%2Fwww.hebrewseniorlife.org%2Frehab-services-boston%2F%22%3EHebrew+Rehabilitation+Center%3C%2Fa%3E%0D%0A%09%09%09A%3A+Thanks%2C+I%E2%80%99m+done+with+this.%0D%0A%09%09%09%09Q%281.1.3.1.1%29%3AGOTO%3Aend%0D%0A%09%09%09A%3A+I+want+to+keep+searching+the+resources.%0D%0A%09%09%09%09Q%281.1.3.1.2%29%3AGOTO%3A1.1%0D%0A%09%09A%3A+No.+%0D%0A%09%09%09Q%281.1.3.2%29%3A+Unfortunately%2C+this+QnA+is+only+focused+on+the+Boston+area.+Do+you+want+to+keep+searching+for+programs%3F%0D%0A%09%09%09A%3A+Yes.%0D%0A%09%09%09%09Q%281.1.3.2.1%29%3AGOTO%3A1.1%0D%0A%09%09%09A%3A+No.%0D%0A%09%09%09%09Q%281.1.3.2.2%29%3AGOTO%3Aend%0D%0A%09A%28community%29%3A+Community+Service%0D%0A%09%09Q%281.1.4%29%3A+Are+you+interested+in+or+in+need+of+completing+community+service+in+the+Boston+area%3F%0D%0A%09%09A%3A+Yes.%0D%0A%09%09%09Q%281.1.4.1%29%3A+Here+are+list+of+programs+in+need+of+volunteers.+%3Cbr%3E%3Cbr%3E%3Ca+href%3D%22http%3A%2F%2Fbostonkroc.salvationarmy.org%2F%22%3EKroc+Center%3C%2Fa%3E%3Cbr%3E%3Cbr%3E%3Ca+href%3D%22http%3A%2F%2Fwww.pinestreetinn.org%2F%22%3EPine+St.+Inn%3C%2Fa%3E%3Cbr%3E%3Cbr%3E%3Ca+href%3D%22https%3A%2F%2Fwww.foodpantries.org%2Fci%2Fma-boston%2F%22%3EFood+Pantries%3C%2Fa%3E%3Cbr%3E%3Cbr%3E%3Ca+href%3D%22https%3A%2F%2Fwww.bostoncares.org%2F%22%3EBoston+Cares%3C%2Fa%3E%0D%0A%09%09%09A%3A+Thanks%2C+I%E2%80%99m+done+with+this.%0D%0A%09%09%09%09Q%281.1.4.1.1%29%3AGOTO%3Aend%0D%0A%09%09%09A%3A+I+want+to+keep+searching+the+resources.%0D%0A%09%09%09%09Q%281.1.4.1.2%29%3AGOTO%3A1.1%0D%0A%09%09A%3A+No%2C+I+want+to+complete+it+outside+of+Boston.%0D%0A%09%09%09Q%281.1.4.2%29%3A+Unfortunately%2C+this+QnA+only+focuses+on+the+Boston+area.+Do+you+want+to+keep+searching+for+programs%3F%0D%0A%09%09%09A%3A+Yes.%0D%0A%09%09%09%09Q%281.1.4.2.1%29%3AGOTO%3A1.1%0D%0A%09%09%09A%3A+No.%0D%0A%09%09%09%09Q%281.1.4.2.2%29%3AGOTO%3Aend%0D%0A%09A%28health%29%3A+Health+Clinic%0D%0A%09%09Q%281.1.5%29%3A+Here+are+a+list+of+judgment-free+clinics.+%3Cbr%3E%3Cbr%3E%3Ca+href%3D%22http%3A%2F%2Fsidneyborum.org%2Fcare%2F%22%3ESidney+Borum+Clinic%3C%2Fa%3E%3Cbr%3E%3Cbr%3E%3Ca+href%3Dhttp%3A%2F%2Fwww.bphc.org%2Fwhatwedo%2Fhomelessness%2Fhomeless-services%2FPages%2Flocations.aspx%2F%3EWoods+Mullen+Shelter%3C%2Fa%3E%0D%0A%09%09A%3A+Thanks%2C+I%E2%80%99m+done+with+this.%0D%0A%09%09%09Q%281.1.5.1%29%3AGOTO%3Aend%0D%0A%09%09A%3A+I+want+to+keep+searching+the+resources.%0D%0A%09%09%09Q%281.1.5.2%29%3AGOTO%3A1.1%0D%0A%09A%28all+set%29%3A+I+am+done+searching.%0D%0A%09%09Q%281.1.6%29%3AGOTO%3Aend%0D%0AA%3A+No.%0D%0A%09Q%281.2%29%3AGOTO%3A2%0D%0AQ%282%29%3A+If+you+are+looking+for+juvenile+services%2C+please+use+Nicole+Siino%E2%80%99s+website+application+for+available+juvenile+resources.%0D%0AQ%28end%29%3A+Thank+you+for+participating%21%0D%0A</div><div id="ondeck" name="ondeck"><div id='Q-1' name='Q-1' style='display:none;'> Are you 18 years or older?
</div><div id='Q-1.1' name='Q-1.1' style='display:none;'> I will provide a list of resources in the Boston area that you can utilize. What are you interested in?
</div><div id='Q-1.1.1' name='Q-1.1.1' style='display:none;'> Pick the field you’re most interested in.
</div><div id='Q-1.1.1.1' name='Q-1.1.1.1' style='display:none;'> Here are some apprentice and training programs in the Greater Boston area. <br><br><a href="https://www.peoplesacademyinc.org">The Peoples Academy</a> <br><br><a href="https://buildingpathwaysboston.org/programs/">BuildingPathWays</a><br><br><a href="http://www.youthbuildboston.org/new-programs/">Youth Build</a>. 
</div><div id='Q-1.1.1.1.1' name='Q-1.1.1.1.1' style='display:none;'>GOTO:3</div><div id='Q-1.1.1.1.2' name='Q-1.1.1.1.2' style='display:none;'>GOTO:1.1</div><div id='Q-1.1.1.2' name='Q-1.1.1.2' style='display:none;'> <a href="https://ne-cat.org/culinary-arts-job-training/">NECAT</a><br><br><a href="http://bostonkroc.salvationarmy.org/BostonKroc/Culinary/">Kroc Center Culinary Arts Training Center</a> 
</div><div id='Q-1.1.1.2.1' name='Q-1.1.1.2.1' style='display:none;'>GOTO:3</div><div id='Q-1.1.1.2.2' name='Q-1.1.1.2.2' style='display:none;'>GOTO:1.1</div><div id='Q-1.1.1.3' name='Q-1.1.1.3' style='display:none;'> Check out Boston’s career services program or Boston Public Health Commission’s Job Training/Education<br><br><a href="https://www.bostoncareerlink.org/index.php?option=com_content&view=article&id=1&Itemid=2/">Boston Career Link</a><br><br><a href="http://www.bphc.org/whatwedo/homelessness/homeless-services/Pages/Job-Training-and-Education.aspx/">Boston Public Health Commission</a>
</div><div id='Q-1.1.1.3.1' name='Q-1.1.1.3.1' style='display:none;'>GOTO:3</div><div id='Q-1.1.1.3.2' name='Q-1.1.1.3.2' style='display:none;'>GOTO:1.1</div><div id='Q-1.1.2' name='Q-1.1.2' style='display:none;'> Are you interested in getting your HiSET, GED, or high school diploma?
</div><div id='Q-1.1.2.1' name='Q-1.1.2.1' style='display:none;'> This hotline will help you figure the program that will benefit you the most! <a href="http://massliteracyhotline.org/hotline//">Massachusetts Literacy Hotline</a>
</div><div id='Q-1.1.2.1.1' name='Q-1.1.2.1.1' style='display:none;'>GOTO:3</div><div id='Q-1.1.2.1.2' name='Q-1.1.2.1.2' style='display:none;'>GOTO:1.1</div><div id='Q-1.1.2.2' name='Q-1.1.2.2' style='display:none;'> Do you want to keep searching the resources?
</div><div id='Q-1.1.2.2.1' name='Q-1.1.2.2.1' style='display:none;'>GOTO:1.1</div><div id='Q-1.1.2.2.2' name='Q-1.1.2.2.2' style='display:none;'>GOTO:3</div><div id='Q-1.1.3' name='Q-1.1.3' style='display:none;'> Are you interested in participating in a program in Boston?
</div><div id='Q-1.1.3.1' name='Q-1.1.3.1' style='display:none;'> Here are a list of rehabilitation programs in Boston. <br><br> <a href="http://spauldingrehab.org/locations/spaulding-rehabilitation-hospital/">Spaulding</a><br><br><a href="http://www.bidmc.org/Centers-and-Departments/Departments/Patient-And-Family-Care-Services/Rehabilitation-Services/Inpatient-Rehabilitation-Services.aspx/">Beth Israel Deaconess Medical Center</a><br><br><a href="http://www.hebrewseniorlife.org/rehab-services-boston/">Hebrew Rehabilitation Center</a>
</div><div id='Q-1.1.3.1.1' name='Q-1.1.3.1.1' style='display:none;'>GOTO:3</div><div id='Q-1.1.3.1.2' name='Q-1.1.3.1.2' style='display:none;'>GOTO:1.1</div><div id='Q-1.1.3.2' name='Q-1.1.3.2' style='display:none;'> Unfortunately, this QnA is only focused on the Boston area. Do you want to keep searching for programs?
</div><div id='Q-1.1.3.2.1' name='Q-1.1.3.2.1' style='display:none;'>GOTO:1.1</div><div id='Q-1.1.3.2.2' name='Q-1.1.3.2.2' style='display:none;'>GOTO:3</div><div id='Q-1.1.4' name='Q-1.1.4' style='display:none;'> Are you interested in or in need of completing community service in the Boston area?
</div><div id='Q-1.1.4.1' name='Q-1.1.4.1' style='display:none;'> Here are list of programs in need of volunteers. <br><br><a href="http://bostonkroc.salvationarmy.org/">Kroc Center</a><br><br><a href="http://www.pinestreetinn.org/">Pine St. Inn</a><br><br><a href="https://www.foodpantries.org/ci/ma-boston/">Food Pantries</a><br><br><a href="https://www.bostoncares.org/">Boston Cares</a>
</div><div id='Q-1.1.4.1.1' name='Q-1.1.4.1.1' style='display:none;'>GOTO:3</div><div id='Q-1.1.4.1.2' name='Q-1.1.4.1.2' style='display:none;'>GOTO:1.1</div><div id='Q-1.1.4.2' name='Q-1.1.4.2' style='display:none;'> Unfortunately, this QnA only focuses on the Boston area. Do you want to keep searching for programs?
</div><div id='Q-1.1.4.2.1' name='Q-1.1.4.2.1' style='display:none;'>GOTO:1.1</div><div id='Q-1.1.4.2.2' name='Q-1.1.4.2.2' style='display:none;'>GOTO:3</div><div id='Q-1.1.5' name='Q-1.1.5' style='display:none;'> Here are a list of judgment-free clinics. <br><br><a href="http://sidneyborum.org/care/">Sidney Borum Clinic</a><br><br><a href=http://www.bphc.org/whatwedo/homelessness/homeless-services/Pages/locations.aspx/>Woods Mullen Shelter</a>
</div><div id='Q-1.1.5.1' name='Q-1.1.5.1' style='display:none;'>GOTO:3</div><div id='Q-1.1.5.2' name='Q-1.1.5.2' style='display:none;'>GOTO:1.1</div><div id='Q-1.1.6' name='Q-1.1.6' style='display:none;'>GOTO:3</div><div id='Q-1.2' name='Q-1.2' style='display:none;'>GOTO:2</div><div id='Q-2' name='Q-2' style='display:none;'> If you are looking for juvenile services, please use Nicole Siino’s website application for available juvenile resources.
</div><div id='Q-3' name='Q-3' style='display:none;'> Thank you for participating!
</div><div id='A-1.1' name='A-1.1' style='display:none;'> Yes.
</div><div id='A-href-1.1' name='A-href-1.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1' name='A-target-1.1' style='display:none;'></div><div id='X-1.1' name='X-1.1' style='display:none;'>Yes.</div><div id='A-1.1.1' name='A-1.1.1' style='display:none;'> Job Training
</div><div id='A-href-1.1.1' name='A-href-1.1.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.1' name='A-target-1.1.1' style='display:none;'></div><div id='X-1.1.1' name='X-1.1.1' style='display:none;'>job training</div><div id='A-1.1.1.1' name='A-1.1.1.1' style='display:none;'> Construction
</div><div id='A-href-1.1.1.1' name='A-href-1.1.1.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.1.1' name='A-target-1.1.1.1' style='display:none;'></div><div id='X-1.1.1.1' name='X-1.1.1.1' style='display:none;'>construction</div><div id='A-1.1.1.1.1' name='A-1.1.1.1.1' style='display:none;'> Thanks, I’m done with this.
</div><div id='A-href-1.1.1.1.1' name='A-href-1.1.1.1.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.1.1.1' name='A-target-1.1.1.1.1' style='display:none;'></div><div id='X-1.1.1.1.1' name='X-1.1.1.1.1' style='display:none;'>Thanks, I’m done with this.</div><div id='A-1.1.1.1.2' name='A-1.1.1.1.2' style='display:none;'> I want to keep searching the resources.
</div><div id='A-href-1.1.1.1.2' name='A-href-1.1.1.1.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.1.1.2' name='A-target-1.1.1.1.2' style='display:none;'></div><div id='X-1.1.1.1.2' name='X-1.1.1.1.2' style='display:none;'>I want to keep searching the resources.</div><div id='A-1.1.1.2' name='A-1.1.1.2' style='display:none;'> Culinary Arts
</div><div id='A-href-1.1.1.2' name='A-href-1.1.1.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.1.2' name='A-target-1.1.1.2' style='display:none;'></div><div id='X-1.1.1.2' name='X-1.1.1.2' style='display:none;'>food</div><div id='A-1.1.1.2.1' name='A-1.1.1.2.1' style='display:none;'> Thanks, I’m done with this.
</div><div id='A-href-1.1.1.2.1' name='A-href-1.1.1.2.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.1.2.1' name='A-target-1.1.1.2.1' style='display:none;'></div><div id='X-1.1.1.2.1' name='X-1.1.1.2.1' style='display:none;'>Thanks, I’m done with this.</div><div id='A-1.1.1.2.2' name='A-1.1.1.2.2' style='display:none;'> I want to keep searching the resources.
</div><div id='A-href-1.1.1.2.2' name='A-href-1.1.1.2.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.1.2.2' name='A-target-1.1.1.2.2' style='display:none;'></div><div id='X-1.1.1.2.2' name='X-1.1.1.2.2' style='display:none;'>I want to keep searching the resources.</div><div id='A-1.1.1.3' name='A-1.1.1.3' style='display:none;'> I’m unsure
</div><div id='A-href-1.1.1.3' name='A-href-1.1.1.3' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.1.3' name='A-target-1.1.1.3' style='display:none;'></div><div id='X-1.1.1.3' name='X-1.1.1.3' style='display:none;'>unsure</div><div id='A-1.1.1.3.1' name='A-1.1.1.3.1' style='display:none;'> Thanks, I’m done with this.
</div><div id='A-href-1.1.1.3.1' name='A-href-1.1.1.3.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.1.3.1' name='A-target-1.1.1.3.1' style='display:none;'></div><div id='X-1.1.1.3.1' name='X-1.1.1.3.1' style='display:none;'>Thanks, I’m done with this.</div><div id='A-1.1.1.3.2' name='A-1.1.1.3.2' style='display:none;'> I want to keep searching the resources.
</div><div id='A-href-1.1.1.3.2' name='A-href-1.1.1.3.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.1.3.2' name='A-target-1.1.1.3.2' style='display:none;'></div><div id='X-1.1.1.3.2' name='X-1.1.1.3.2' style='display:none;'>I want to keep searching the resources.</div><div id='A-1.1.2' name='A-1.1.2' style='display:none;'> Alternative Education
</div><div id='A-href-1.1.2' name='A-href-1.1.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.2' name='A-target-1.1.2' style='display:none;'></div><div id='X-1.1.2' name='X-1.1.2' style='display:none;'>Alternative education</div><div id='A-1.1.2.1' name='A-1.1.2.1' style='display:none;'> Yes
</div><div id='A-href-1.1.2.1' name='A-href-1.1.2.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.2.1' name='A-target-1.1.2.1' style='display:none;'></div><div id='X-1.1.2.1' name='X-1.1.2.1' style='display:none;'>Yes</div><div id='A-1.1.2.1.1' name='A-1.1.2.1.1' style='display:none;'> Thanks, I’m done with this.
</div><div id='A-href-1.1.2.1.1' name='A-href-1.1.2.1.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.2.1.1' name='A-target-1.1.2.1.1' style='display:none;'></div><div id='X-1.1.2.1.1' name='X-1.1.2.1.1' style='display:none;'>Thanks, I’m done with this.</div><div id='A-1.1.2.1.2' name='A-1.1.2.1.2' style='display:none;'> I want to keep searching the resources.
</div><div id='A-href-1.1.2.1.2' name='A-href-1.1.2.1.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.2.1.2' name='A-target-1.1.2.1.2' style='display:none;'></div><div id='X-1.1.2.1.2' name='X-1.1.2.1.2' style='display:none;'>I want to keep searching the resources.</div><div id='A-1.1.2.2' name='A-1.1.2.2' style='display:none;'> No.
</div><div id='A-href-1.1.2.2' name='A-href-1.1.2.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.2.2' name='A-target-1.1.2.2' style='display:none;'></div><div id='X-1.1.2.2' name='X-1.1.2.2' style='display:none;'>No.</div><div id='A-1.1.2.2.1' name='A-1.1.2.2.1' style='display:none;'> Yes please!
</div><div id='A-href-1.1.2.2.1' name='A-href-1.1.2.2.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.2.2.1' name='A-target-1.1.2.2.1' style='display:none;'></div><div id='X-1.1.2.2.1' name='X-1.1.2.2.1' style='display:none;'>Yes please!</div><div id='A-1.1.2.2.2' name='A-1.1.2.2.2' style='display:none;'> No thanks, I’m all set.
</div><div id='A-href-1.1.2.2.2' name='A-href-1.1.2.2.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.2.2.2' name='A-target-1.1.2.2.2' style='display:none;'></div><div id='X-1.1.2.2.2' name='X-1.1.2.2.2' style='display:none;'>No thanks, I’m all set.</div><div id='A-1.1.3' name='A-1.1.3' style='display:none;'> Rehabilitation Facility
</div><div id='A-href-1.1.3' name='A-href-1.1.3' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.3' name='A-target-1.1.3' style='display:none;'></div><div id='X-1.1.3' name='X-1.1.3' style='display:none;'>rehab</div><div id='A-1.1.3.1' name='A-1.1.3.1' style='display:none;'> Yes.
</div><div id='A-href-1.1.3.1' name='A-href-1.1.3.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.3.1' name='A-target-1.1.3.1' style='display:none;'></div><div id='X-1.1.3.1' name='X-1.1.3.1' style='display:none;'>Yes.</div><div id='A-1.1.3.1.1' name='A-1.1.3.1.1' style='display:none;'> Thanks, I’m done with this.
</div><div id='A-href-1.1.3.1.1' name='A-href-1.1.3.1.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.3.1.1' name='A-target-1.1.3.1.1' style='display:none;'></div><div id='X-1.1.3.1.1' name='X-1.1.3.1.1' style='display:none;'>Thanks, I’m done with this.</div><div id='A-1.1.3.1.2' name='A-1.1.3.1.2' style='display:none;'> I want to keep searching the resources.
</div><div id='A-href-1.1.3.1.2' name='A-href-1.1.3.1.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.3.1.2' name='A-target-1.1.3.1.2' style='display:none;'></div><div id='X-1.1.3.1.2' name='X-1.1.3.1.2' style='display:none;'>I want to keep searching the resources.</div><div id='A-1.1.3.2' name='A-1.1.3.2' style='display:none;'> No. 
</div><div id='A-href-1.1.3.2' name='A-href-1.1.3.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.3.2' name='A-target-1.1.3.2' style='display:none;'></div><div id='X-1.1.3.2' name='X-1.1.3.2' style='display:none;'>No.</div><div id='A-1.1.3.2.1' name='A-1.1.3.2.1' style='display:none;'> Yes.
</div><div id='A-href-1.1.3.2.1' name='A-href-1.1.3.2.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.3.2.1' name='A-target-1.1.3.2.1' style='display:none;'></div><div id='X-1.1.3.2.1' name='X-1.1.3.2.1' style='display:none;'>Yes.</div><div id='A-1.1.3.2.2' name='A-1.1.3.2.2' style='display:none;'> No.
</div><div id='A-href-1.1.3.2.2' name='A-href-1.1.3.2.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.3.2.2' name='A-target-1.1.3.2.2' style='display:none;'></div><div id='X-1.1.3.2.2' name='X-1.1.3.2.2' style='display:none;'>No.</div><div id='A-1.1.4' name='A-1.1.4' style='display:none;'> Community Service
</div><div id='A-href-1.1.4' name='A-href-1.1.4' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.4' name='A-target-1.1.4' style='display:none;'></div><div id='X-1.1.4' name='X-1.1.4' style='display:none;'>community</div><div id='A-1.1.4.1' name='A-1.1.4.1' style='display:none;'> Yes.
</div><div id='A-href-1.1.4.1' name='A-href-1.1.4.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.4.1' name='A-target-1.1.4.1' style='display:none;'></div><div id='X-1.1.4.1' name='X-1.1.4.1' style='display:none;'>Yes.</div><div id='A-1.1.4.1.1' name='A-1.1.4.1.1' style='display:none;'> Thanks, I’m done with this.
</div><div id='A-href-1.1.4.1.1' name='A-href-1.1.4.1.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.4.1.1' name='A-target-1.1.4.1.1' style='display:none;'></div><div id='X-1.1.4.1.1' name='X-1.1.4.1.1' style='display:none;'>Thanks, I’m done with this.</div><div id='A-1.1.4.1.2' name='A-1.1.4.1.2' style='display:none;'> I want to keep searching the resources.
</div><div id='A-href-1.1.4.1.2' name='A-href-1.1.4.1.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.4.1.2' name='A-target-1.1.4.1.2' style='display:none;'></div><div id='X-1.1.4.1.2' name='X-1.1.4.1.2' style='display:none;'>I want to keep searching the resources.</div><div id='A-1.1.4.2' name='A-1.1.4.2' style='display:none;'> No, I want to complete it outside of Boston.
</div><div id='A-href-1.1.4.2' name='A-href-1.1.4.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.4.2' name='A-target-1.1.4.2' style='display:none;'></div><div id='X-1.1.4.2' name='X-1.1.4.2' style='display:none;'>No, I want to complete it outside of Boston.</div><div id='A-1.1.4.2.1' name='A-1.1.4.2.1' style='display:none;'> Yes.
</div><div id='A-href-1.1.4.2.1' name='A-href-1.1.4.2.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.4.2.1' name='A-target-1.1.4.2.1' style='display:none;'></div><div id='X-1.1.4.2.1' name='X-1.1.4.2.1' style='display:none;'>Yes.</div><div id='A-1.1.4.2.2' name='A-1.1.4.2.2' style='display:none;'> No.
</div><div id='A-href-1.1.4.2.2' name='A-href-1.1.4.2.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.4.2.2' name='A-target-1.1.4.2.2' style='display:none;'></div><div id='X-1.1.4.2.2' name='X-1.1.4.2.2' style='display:none;'>No.</div><div id='A-1.1.5' name='A-1.1.5' style='display:none;'> Health Clinic
</div><div id='A-href-1.1.5' name='A-href-1.1.5' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.5' name='A-target-1.1.5' style='display:none;'></div><div id='X-1.1.5' name='X-1.1.5' style='display:none;'>health</div><div id='A-1.1.5.1' name='A-1.1.5.1' style='display:none;'> Thanks, I’m done with this.
</div><div id='A-href-1.1.5.1' name='A-href-1.1.5.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.5.1' name='A-target-1.1.5.1' style='display:none;'></div><div id='X-1.1.5.1' name='X-1.1.5.1' style='display:none;'>Thanks, I’m done with this.</div><div id='A-1.1.5.2' name='A-1.1.5.2' style='display:none;'> I want to keep searching the resources.
</div><div id='A-href-1.1.5.2' name='A-href-1.1.5.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.5.2' name='A-target-1.1.5.2' style='display:none;'></div><div id='X-1.1.5.2' name='X-1.1.5.2' style='display:none;'>I want to keep searching the resources.</div><div id='A-1.1.6' name='A-1.1.6' style='display:none;'> I am done searching.
</div><div id='A-href-1.1.6' name='A-href-1.1.6' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.6' name='A-target-1.1.6' style='display:none;'></div><div id='X-1.1.6' name='X-1.1.6' style='display:none;'>all set</div><div id='A-1.2' name='A-1.2' style='display:none;'> No.
</div><div id='A-href-1.2' name='A-href-1.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.2' name='A-target-1.2' style='display:none;'></div><div id='X-1.2' name='X-1.2' style='display:none;'>No.</div>
<script>
	var QVnames = [['1','1'],['1.1','1.1'],['1.1.1','1.1.1'],['1.1.1.1','1.1.1.1'],['1.1.1.1.1','1.1.1.1.1'],['1.1.1.1.2','1.1.1.1.2'],['1.1.1.2','1.1.1.2'],['1.1.1.2.1','1.1.1.2.1'],['1.1.1.2.2','1.1.1.2.2'],['1.1.1.3','1.1.1.3'],['1.1.1.3.1','1.1.1.3.1'],['1.1.1.3.2','1.1.1.3.2'],['1.1.2','1.1.2'],['1.1.2.1','1.1.2.1'],['1.1.2.1.1','1.1.2.1.1'],['1.1.2.1.2','1.1.2.1.2'],['1.1.2.2','1.1.2.2'],['1.1.2.2.1','1.1.2.2.1'],['1.1.2.2.2','1.1.2.2.2'],['1.1.3','1.1.3'],['1.1.3.1','1.1.3.1'],['1.1.3.1.1','1.1.3.1.1'],['1.1.3.1.2','1.1.3.1.2'],['1.1.3.2','1.1.3.2'],['1.1.3.2.1','1.1.3.2.1'],['1.1.3.2.2','1.1.3.2.2'],['1.1.4','1.1.4'],['1.1.4.1','1.1.4.1'],['1.1.4.1.1','1.1.4.1.1'],['1.1.4.1.2','1.1.4.1.2'],['1.1.4.2','1.1.4.2'],['1.1.4.2.1','1.1.4.2.1'],['1.1.4.2.2','1.1.4.2.2'],['1.1.5','1.1.5'],['1.1.5.1','1.1.5.1'],['1.1.5.2','1.1.5.2'],['1.1.6','1.1.6'],['1.2','1.2'],['2','2'],['3','end']];
</script>
</div><textarea id="original" name="original" style="display:none;" disabled="disabled"><div id='Q-1' name='Q-1' style='display:none;'> Are you 18 years or older?
</div><div id='Q-1.1' name='Q-1.1' style='display:none;'> I will provide a list of resources in the Boston area that you can utilize. What are you interested in?
</div><div id='Q-1.1.1' name='Q-1.1.1' style='display:none;'> Pick the field you’re most interested in.
</div><div id='Q-1.1.1.1' name='Q-1.1.1.1' style='display:none;'> Here are some apprentice and training programs in the Greater Boston area. <br><br><a href="https://www.peoplesacademyinc.org">The Peoples Academy</a> <br><br><a href="https://buildingpathwaysboston.org/programs/">BuildingPathWays</a><br><br><a href="http://www.youthbuildboston.org/new-programs/">Youth Build</a>. 
</div><div id='Q-1.1.1.1.1' name='Q-1.1.1.1.1' style='display:none;'>GOTO:3</div><div id='Q-1.1.1.1.2' name='Q-1.1.1.1.2' style='display:none;'>GOTO:1.1</div><div id='Q-1.1.1.2' name='Q-1.1.1.2' style='display:none;'> <a href="https://ne-cat.org/culinary-arts-job-training/">NECAT</a><br><br><a href="http://bostonkroc.salvationarmy.org/BostonKroc/Culinary/">Kroc Center Culinary Arts Training Center</a> 
</div><div id='Q-1.1.1.2.1' name='Q-1.1.1.2.1' style='display:none;'>GOTO:3</div><div id='Q-1.1.1.2.2' name='Q-1.1.1.2.2' style='display:none;'>GOTO:1.1</div><div id='Q-1.1.1.3' name='Q-1.1.1.3' style='display:none;'> Check out Boston’s career services program or Boston Public Health Commission’s Job Training/Education<br><br><a href="https://www.bostoncareerlink.org/index.php?option=com_content&view=article&id=1&Itemid=2/">Boston Career Link</a><br><br><a href="http://www.bphc.org/whatwedo/homelessness/homeless-services/Pages/Job-Training-and-Education.aspx/">Boston Public Health Commission</a>
</div><div id='Q-1.1.1.3.1' name='Q-1.1.1.3.1' style='display:none;'>GOTO:3</div><div id='Q-1.1.1.3.2' name='Q-1.1.1.3.2' style='display:none;'>GOTO:1.1</div><div id='Q-1.1.2' name='Q-1.1.2' style='display:none;'> Are you interested in getting your HiSET, GED, or high school diploma?
</div><div id='Q-1.1.2.1' name='Q-1.1.2.1' style='display:none;'> This hotline will help you figure the program that will benefit you the most! <a href="http://massliteracyhotline.org/hotline//">Massachusetts Literacy Hotline</a>
</div><div id='Q-1.1.2.1.1' name='Q-1.1.2.1.1' style='display:none;'>GOTO:3</div><div id='Q-1.1.2.1.2' name='Q-1.1.2.1.2' style='display:none;'>GOTO:1.1</div><div id='Q-1.1.2.2' name='Q-1.1.2.2' style='display:none;'> Do you want to keep searching the resources?
</div><div id='Q-1.1.2.2.1' name='Q-1.1.2.2.1' style='display:none;'>GOTO:1.1</div><div id='Q-1.1.2.2.2' name='Q-1.1.2.2.2' style='display:none;'>GOTO:3</div><div id='Q-1.1.3' name='Q-1.1.3' style='display:none;'> Are you interested in participating in a program in Boston?
</div><div id='Q-1.1.3.1' name='Q-1.1.3.1' style='display:none;'> Here are a list of rehabilitation programs in Boston. <br><br> <a href="http://spauldingrehab.org/locations/spaulding-rehabilitation-hospital/">Spaulding</a><br><br><a href="http://www.bidmc.org/Centers-and-Departments/Departments/Patient-And-Family-Care-Services/Rehabilitation-Services/Inpatient-Rehabilitation-Services.aspx/">Beth Israel Deaconess Medical Center</a><br><br><a href="http://www.hebrewseniorlife.org/rehab-services-boston/">Hebrew Rehabilitation Center</a>
</div><div id='Q-1.1.3.1.1' name='Q-1.1.3.1.1' style='display:none;'>GOTO:3</div><div id='Q-1.1.3.1.2' name='Q-1.1.3.1.2' style='display:none;'>GOTO:1.1</div><div id='Q-1.1.3.2' name='Q-1.1.3.2' style='display:none;'> Unfortunately, this QnA is only focused on the Boston area. Do you want to keep searching for programs?
</div><div id='Q-1.1.3.2.1' name='Q-1.1.3.2.1' style='display:none;'>GOTO:1.1</div><div id='Q-1.1.3.2.2' name='Q-1.1.3.2.2' style='display:none;'>GOTO:3</div><div id='Q-1.1.4' name='Q-1.1.4' style='display:none;'> Are you interested in or in need of completing community service in the Boston area?
</div><div id='Q-1.1.4.1' name='Q-1.1.4.1' style='display:none;'> Here are list of programs in need of volunteers. <br><br><a href="http://bostonkroc.salvationarmy.org/">Kroc Center</a><br><br><a href="http://www.pinestreetinn.org/">Pine St. Inn</a><br><br><a href="https://www.foodpantries.org/ci/ma-boston/">Food Pantries</a><br><br><a href="https://www.bostoncares.org/">Boston Cares</a>
</div><div id='Q-1.1.4.1.1' name='Q-1.1.4.1.1' style='display:none;'>GOTO:3</div><div id='Q-1.1.4.1.2' name='Q-1.1.4.1.2' style='display:none;'>GOTO:1.1</div><div id='Q-1.1.4.2' name='Q-1.1.4.2' style='display:none;'> Unfortunately, this QnA only focuses on the Boston area. Do you want to keep searching for programs?
</div><div id='Q-1.1.4.2.1' name='Q-1.1.4.2.1' style='display:none;'>GOTO:1.1</div><div id='Q-1.1.4.2.2' name='Q-1.1.4.2.2' style='display:none;'>GOTO:3</div><div id='Q-1.1.5' name='Q-1.1.5' style='display:none;'> Here are a list of judgment-free clinics. <br><br><a href="http://sidneyborum.org/care/">Sidney Borum Clinic</a><br><br><a href=http://www.bphc.org/whatwedo/homelessness/homeless-services/Pages/locations.aspx/>Woods Mullen Shelter</a>
</div><div id='Q-1.1.5.1' name='Q-1.1.5.1' style='display:none;'>GOTO:3</div><div id='Q-1.1.5.2' name='Q-1.1.5.2' style='display:none;'>GOTO:1.1</div><div id='Q-1.1.6' name='Q-1.1.6' style='display:none;'>GOTO:3</div><div id='Q-1.2' name='Q-1.2' style='display:none;'>GOTO:2</div><div id='Q-2' name='Q-2' style='display:none;'> If you are looking for juvenile services, please use Nicole Siino’s website application for available juvenile resources.
</div><div id='Q-3' name='Q-3' style='display:none;'> Thank you for participating!
</div><div id='A-1.1' name='A-1.1' style='display:none;'> Yes.
</div><div id='A-href-1.1' name='A-href-1.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1' name='A-target-1.1' style='display:none;'></div><div id='X-1.1' name='X-1.1' style='display:none;'>Yes.</div><div id='A-1.1.1' name='A-1.1.1' style='display:none;'> Job Training
</div><div id='A-href-1.1.1' name='A-href-1.1.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.1' name='A-target-1.1.1' style='display:none;'></div><div id='X-1.1.1' name='X-1.1.1' style='display:none;'>job training</div><div id='A-1.1.1.1' name='A-1.1.1.1' style='display:none;'> Construction
</div><div id='A-href-1.1.1.1' name='A-href-1.1.1.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.1.1' name='A-target-1.1.1.1' style='display:none;'></div><div id='X-1.1.1.1' name='X-1.1.1.1' style='display:none;'>construction</div><div id='A-1.1.1.1.1' name='A-1.1.1.1.1' style='display:none;'> Thanks, I’m done with this.
</div><div id='A-href-1.1.1.1.1' name='A-href-1.1.1.1.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.1.1.1' name='A-target-1.1.1.1.1' style='display:none;'></div><div id='X-1.1.1.1.1' name='X-1.1.1.1.1' style='display:none;'>Thanks, I’m done with this.</div><div id='A-1.1.1.1.2' name='A-1.1.1.1.2' style='display:none;'> I want to keep searching the resources.
</div><div id='A-href-1.1.1.1.2' name='A-href-1.1.1.1.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.1.1.2' name='A-target-1.1.1.1.2' style='display:none;'></div><div id='X-1.1.1.1.2' name='X-1.1.1.1.2' style='display:none;'>I want to keep searching the resources.</div><div id='A-1.1.1.2' name='A-1.1.1.2' style='display:none;'> Culinary Arts
</div><div id='A-href-1.1.1.2' name='A-href-1.1.1.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.1.2' name='A-target-1.1.1.2' style='display:none;'></div><div id='X-1.1.1.2' name='X-1.1.1.2' style='display:none;'>food</div><div id='A-1.1.1.2.1' name='A-1.1.1.2.1' style='display:none;'> Thanks, I’m done with this.
</div><div id='A-href-1.1.1.2.1' name='A-href-1.1.1.2.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.1.2.1' name='A-target-1.1.1.2.1' style='display:none;'></div><div id='X-1.1.1.2.1' name='X-1.1.1.2.1' style='display:none;'>Thanks, I’m done with this.</div><div id='A-1.1.1.2.2' name='A-1.1.1.2.2' style='display:none;'> I want to keep searching the resources.
</div><div id='A-href-1.1.1.2.2' name='A-href-1.1.1.2.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.1.2.2' name='A-target-1.1.1.2.2' style='display:none;'></div><div id='X-1.1.1.2.2' name='X-1.1.1.2.2' style='display:none;'>I want to keep searching the resources.</div><div id='A-1.1.1.3' name='A-1.1.1.3' style='display:none;'> I’m unsure
</div><div id='A-href-1.1.1.3' name='A-href-1.1.1.3' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.1.3' name='A-target-1.1.1.3' style='display:none;'></div><div id='X-1.1.1.3' name='X-1.1.1.3' style='display:none;'>unsure</div><div id='A-1.1.1.3.1' name='A-1.1.1.3.1' style='display:none;'> Thanks, I’m done with this.
</div><div id='A-href-1.1.1.3.1' name='A-href-1.1.1.3.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.1.3.1' name='A-target-1.1.1.3.1' style='display:none;'></div><div id='X-1.1.1.3.1' name='X-1.1.1.3.1' style='display:none;'>Thanks, I’m done with this.</div><div id='A-1.1.1.3.2' name='A-1.1.1.3.2' style='display:none;'> I want to keep searching the resources.
</div><div id='A-href-1.1.1.3.2' name='A-href-1.1.1.3.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.1.3.2' name='A-target-1.1.1.3.2' style='display:none;'></div><div id='X-1.1.1.3.2' name='X-1.1.1.3.2' style='display:none;'>I want to keep searching the resources.</div><div id='A-1.1.2' name='A-1.1.2' style='display:none;'> Alternative Education
</div><div id='A-href-1.1.2' name='A-href-1.1.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.2' name='A-target-1.1.2' style='display:none;'></div><div id='X-1.1.2' name='X-1.1.2' style='display:none;'>Alternative education</div><div id='A-1.1.2.1' name='A-1.1.2.1' style='display:none;'> Yes
</div><div id='A-href-1.1.2.1' name='A-href-1.1.2.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.2.1' name='A-target-1.1.2.1' style='display:none;'></div><div id='X-1.1.2.1' name='X-1.1.2.1' style='display:none;'>Yes</div><div id='A-1.1.2.1.1' name='A-1.1.2.1.1' style='display:none;'> Thanks, I’m done with this.
</div><div id='A-href-1.1.2.1.1' name='A-href-1.1.2.1.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.2.1.1' name='A-target-1.1.2.1.1' style='display:none;'></div><div id='X-1.1.2.1.1' name='X-1.1.2.1.1' style='display:none;'>Thanks, I’m done with this.</div><div id='A-1.1.2.1.2' name='A-1.1.2.1.2' style='display:none;'> I want to keep searching the resources.
</div><div id='A-href-1.1.2.1.2' name='A-href-1.1.2.1.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.2.1.2' name='A-target-1.1.2.1.2' style='display:none;'></div><div id='X-1.1.2.1.2' name='X-1.1.2.1.2' style='display:none;'>I want to keep searching the resources.</div><div id='A-1.1.2.2' name='A-1.1.2.2' style='display:none;'> No.
</div><div id='A-href-1.1.2.2' name='A-href-1.1.2.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.2.2' name='A-target-1.1.2.2' style='display:none;'></div><div id='X-1.1.2.2' name='X-1.1.2.2' style='display:none;'>No.</div><div id='A-1.1.2.2.1' name='A-1.1.2.2.1' style='display:none;'> Yes please!
</div><div id='A-href-1.1.2.2.1' name='A-href-1.1.2.2.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.2.2.1' name='A-target-1.1.2.2.1' style='display:none;'></div><div id='X-1.1.2.2.1' name='X-1.1.2.2.1' style='display:none;'>Yes please!</div><div id='A-1.1.2.2.2' name='A-1.1.2.2.2' style='display:none;'> No thanks, I’m all set.
</div><div id='A-href-1.1.2.2.2' name='A-href-1.1.2.2.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.2.2.2' name='A-target-1.1.2.2.2' style='display:none;'></div><div id='X-1.1.2.2.2' name='X-1.1.2.2.2' style='display:none;'>No thanks, I’m all set.</div><div id='A-1.1.3' name='A-1.1.3' style='display:none;'> Rehabilitation Facility
</div><div id='A-href-1.1.3' name='A-href-1.1.3' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.3' name='A-target-1.1.3' style='display:none;'></div><div id='X-1.1.3' name='X-1.1.3' style='display:none;'>rehab</div><div id='A-1.1.3.1' name='A-1.1.3.1' style='display:none;'> Yes.
</div><div id='A-href-1.1.3.1' name='A-href-1.1.3.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.3.1' name='A-target-1.1.3.1' style='display:none;'></div><div id='X-1.1.3.1' name='X-1.1.3.1' style='display:none;'>Yes.</div><div id='A-1.1.3.1.1' name='A-1.1.3.1.1' style='display:none;'> Thanks, I’m done with this.
</div><div id='A-href-1.1.3.1.1' name='A-href-1.1.3.1.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.3.1.1' name='A-target-1.1.3.1.1' style='display:none;'></div><div id='X-1.1.3.1.1' name='X-1.1.3.1.1' style='display:none;'>Thanks, I’m done with this.</div><div id='A-1.1.3.1.2' name='A-1.1.3.1.2' style='display:none;'> I want to keep searching the resources.
</div><div id='A-href-1.1.3.1.2' name='A-href-1.1.3.1.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.3.1.2' name='A-target-1.1.3.1.2' style='display:none;'></div><div id='X-1.1.3.1.2' name='X-1.1.3.1.2' style='display:none;'>I want to keep searching the resources.</div><div id='A-1.1.3.2' name='A-1.1.3.2' style='display:none;'> No. 
</div><div id='A-href-1.1.3.2' name='A-href-1.1.3.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.3.2' name='A-target-1.1.3.2' style='display:none;'></div><div id='X-1.1.3.2' name='X-1.1.3.2' style='display:none;'>No.</div><div id='A-1.1.3.2.1' name='A-1.1.3.2.1' style='display:none;'> Yes.
</div><div id='A-href-1.1.3.2.1' name='A-href-1.1.3.2.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.3.2.1' name='A-target-1.1.3.2.1' style='display:none;'></div><div id='X-1.1.3.2.1' name='X-1.1.3.2.1' style='display:none;'>Yes.</div><div id='A-1.1.3.2.2' name='A-1.1.3.2.2' style='display:none;'> No.
</div><div id='A-href-1.1.3.2.2' name='A-href-1.1.3.2.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.3.2.2' name='A-target-1.1.3.2.2' style='display:none;'></div><div id='X-1.1.3.2.2' name='X-1.1.3.2.2' style='display:none;'>No.</div><div id='A-1.1.4' name='A-1.1.4' style='display:none;'> Community Service
</div><div id='A-href-1.1.4' name='A-href-1.1.4' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.4' name='A-target-1.1.4' style='display:none;'></div><div id='X-1.1.4' name='X-1.1.4' style='display:none;'>community</div><div id='A-1.1.4.1' name='A-1.1.4.1' style='display:none;'> Yes.
</div><div id='A-href-1.1.4.1' name='A-href-1.1.4.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.4.1' name='A-target-1.1.4.1' style='display:none;'></div><div id='X-1.1.4.1' name='X-1.1.4.1' style='display:none;'>Yes.</div><div id='A-1.1.4.1.1' name='A-1.1.4.1.1' style='display:none;'> Thanks, I’m done with this.
</div><div id='A-href-1.1.4.1.1' name='A-href-1.1.4.1.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.4.1.1' name='A-target-1.1.4.1.1' style='display:none;'></div><div id='X-1.1.4.1.1' name='X-1.1.4.1.1' style='display:none;'>Thanks, I’m done with this.</div><div id='A-1.1.4.1.2' name='A-1.1.4.1.2' style='display:none;'> I want to keep searching the resources.
</div><div id='A-href-1.1.4.1.2' name='A-href-1.1.4.1.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.4.1.2' name='A-target-1.1.4.1.2' style='display:none;'></div><div id='X-1.1.4.1.2' name='X-1.1.4.1.2' style='display:none;'>I want to keep searching the resources.</div><div id='A-1.1.4.2' name='A-1.1.4.2' style='display:none;'> No, I want to complete it outside of Boston.
</div><div id='A-href-1.1.4.2' name='A-href-1.1.4.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.4.2' name='A-target-1.1.4.2' style='display:none;'></div><div id='X-1.1.4.2' name='X-1.1.4.2' style='display:none;'>No, I want to complete it outside of Boston.</div><div id='A-1.1.4.2.1' name='A-1.1.4.2.1' style='display:none;'> Yes.
</div><div id='A-href-1.1.4.2.1' name='A-href-1.1.4.2.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.4.2.1' name='A-target-1.1.4.2.1' style='display:none;'></div><div id='X-1.1.4.2.1' name='X-1.1.4.2.1' style='display:none;'>Yes.</div><div id='A-1.1.4.2.2' name='A-1.1.4.2.2' style='display:none;'> No.
</div><div id='A-href-1.1.4.2.2' name='A-href-1.1.4.2.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.4.2.2' name='A-target-1.1.4.2.2' style='display:none;'></div><div id='X-1.1.4.2.2' name='X-1.1.4.2.2' style='display:none;'>No.</div><div id='A-1.1.5' name='A-1.1.5' style='display:none;'> Health Clinic
</div><div id='A-href-1.1.5' name='A-href-1.1.5' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.5' name='A-target-1.1.5' style='display:none;'></div><div id='X-1.1.5' name='X-1.1.5' style='display:none;'>health</div><div id='A-1.1.5.1' name='A-1.1.5.1' style='display:none;'> Thanks, I’m done with this.
</div><div id='A-href-1.1.5.1' name='A-href-1.1.5.1' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.5.1' name='A-target-1.1.5.1' style='display:none;'></div><div id='X-1.1.5.1' name='X-1.1.5.1' style='display:none;'>Thanks, I’m done with this.</div><div id='A-1.1.5.2' name='A-1.1.5.2' style='display:none;'> I want to keep searching the resources.
</div><div id='A-href-1.1.5.2' name='A-href-1.1.5.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.5.2' name='A-target-1.1.5.2' style='display:none;'></div><div id='X-1.1.5.2' name='X-1.1.5.2' style='display:none;'>I want to keep searching the resources.</div><div id='A-1.1.6' name='A-1.1.6' style='display:none;'> I am done searching.
</div><div id='A-href-1.1.6' name='A-href-1.1.6' style='display:none;'>javascript:void('');</div><div id='A-target-1.1.6' name='A-target-1.1.6' style='display:none;'></div><div id='X-1.1.6' name='X-1.1.6' style='display:none;'>all set</div><div id='A-1.2' name='A-1.2' style='display:none;'> No.
</div><div id='A-href-1.2' name='A-href-1.2' style='display:none;'>javascript:void('');</div><div id='A-target-1.2' name='A-target-1.2' style='display:none;'></div><div id='X-1.2' name='X-1.2' style='display:none;'>No.</div>
<script>
	var QVnames = [['1','1'],['1.1','1.1'],['1.1.1','1.1.1'],['1.1.1.1','1.1.1.1'],['1.1.1.1.1','1.1.1.1.1'],['1.1.1.1.2','1.1.1.1.2'],['1.1.1.2','1.1.1.2'],['1.1.1.2.1','1.1.1.2.1'],['1.1.1.2.2','1.1.1.2.2'],['1.1.1.3','1.1.1.3'],['1.1.1.3.1','1.1.1.3.1'],['1.1.1.3.2','1.1.1.3.2'],['1.1.2','1.1.2'],['1.1.2.1','1.1.2.1'],['1.1.2.1.1','1.1.2.1.1'],['1.1.2.1.2','1.1.2.1.2'],['1.1.2.2','1.1.2.2'],['1.1.2.2.1','1.1.2.2.1'],['1.1.2.2.2','1.1.2.2.2'],['1.1.3','1.1.3'],['1.1.3.1','1.1.3.1'],['1.1.3.1.1','1.1.3.1.1'],['1.1.3.1.2','1.1.3.1.2'],['1.1.3.2','1.1.3.2'],['1.1.3.2.1','1.1.3.2.1'],['1.1.3.2.2','1.1.3.2.2'],['1.1.4','1.1.4'],['1.1.4.1','1.1.4.1'],['1.1.4.1.1','1.1.4.1.1'],['1.1.4.1.2','1.1.4.1.2'],['1.1.4.2','1.1.4.2'],['1.1.4.2.1','1.1.4.2.1'],['1.1.4.2.2','1.1.4.2.2'],['1.1.5','1.1.5'],['1.1.5.1','1.1.5.1'],['1.1.5.2','1.1.5.2'],['1.1.6','1.1.6'],['1.2','1.2'],['2','2'],['3','end']];
</script>
</textarea><textarea id="transcript" name="transcript" style="display:none;" disabled="disabled"></textarea><div style="float:left;width:100%;margin:15px 0 0px 0;border-top: solid 1px #ddd;"><div id=credits class=credits style="display:none;"><div class=credit_text></div></div><p align=center> <a href="http://www.qnamarkup.org/" target=_top>code your own</a></p></div></FORM></div></div>
<script type="text/javascript">
	var QNum = 0;
	var Qhtml = "";
	var Dhtml = "";
	var label = "";
	var GOTOfired = 0;
	var path = [];
	var doc_bin = [];
	var convo_bin = [];
	var freetext = 0;
	var goingback = 0;

	$("#conversation input").on("keypress", 'form', function (e) {
    	var code = e.keyCode || e.which;
    	if (code == 13) {
        	e.preventDefault();
        	return false;
    	}
	});

	function answerQ(lb,restart) {
		currentQ = label;
		label = lb;
		Dhtml = 'D-'+label;
		Qhtml = 'Q-'+label;
		var Ahtml = 'A-'+label;
		var Jhtml = 'J-'+QNum;
		var Xhtml = 'X-'+label;
		var Xihtml = 'Xi-'+label;
		
		var input_error = 0;
		if (restart == undefined) {
			var regexp = new RegExp("\<variable\>");
			//if (document.getElementById(Xihtml)) {
			//	console.log("document.getElementById("+Xihtml+").value: "+document.getElementById(Xihtml).value);
			//} else {
			//	console.log("NO document.getElementById("+Xihtml+").value: ");
			//}
			if (document.getElementById(Ahtml).innerHTML.match(regexp)) {
				document.getElementById(Xihtml).value = document.getElementById(Xihtml).value.replace(/(^\s*|\s*$)/,"");
				if (document.getElementById(Xihtml).value == "") {
					input_error = "Your answer appears to be empty.";
					label = currentQ;
				} else {
					document.getElementById(Xihtml).value = document.getElementById(Xihtml).value.replace(/</g,"<");
					document.getElementById(Xihtml).value = document.getElementById(Xihtml).value.replace(/>/g,">");
				}
			} 
		}
			
		if (input_error != 0) {
			alert(input_error);
			document.getElementById(Xihtml).focus();			
		} else {
			if (restart == undefined) {
				document.getElementById('QandA').innerHTML += "<div id=\"break-at-"+QNum+"\" class='frame'><div class='full'><div class='ans_text'>"+document.getElementById(Ahtml).innerHTML+"</div></div><div class='ans_arrow'></div></div></div></div>";
				// insert answer from button
				if (document.getElementById(valueis(currentQ))) {
					document.getElementById(valueis(currentQ)).outerHTML='';
				}
				if (document.getElementById(Xihtml)) {
					document.getElementById('QandA').innerHTML = "<textarea style=\"display:none;\" id=\""+valueis(currentQ)+"\" name=\""+valueis(currentQ)+"\">"+document.getElementById(Xihtml).value+"</textarea>\n" + document.getElementById('QandA').innerHTML				
				} else {
					document.getElementById('QandA').innerHTML = "<textarea style=\"display:none;\" id=\""+valueis(currentQ)+"\" name=\""+valueis(currentQ)+"\">"+document.getElementById(Xhtml).innerHTML+"</textarea>\n" + document.getElementById('QandA').innerHTML
				}
				if (document.getElementById('QandA').innerHTML.match(regexp)) {
				 	var duplicatevars = new RegExp("id=\""+document.getElementById(Xhtml).innerHTML+"(.)*"+document.getElementById(Xhtml).innerHTML+"\"","g");
					document.getElementById('QandA').innerHTML = document.getElementById('QandA').innerHTML.replace(duplicatevars, "");
					document.getElementById('QandA').innerHTML = document.getElementById('QandA').innerHTML.replace(/\<variable\>(\<\/variable\>)?/, "<input type=hidden id=\""+document.getElementById(Xhtml).innerHTML+"\" name=\""+document.getElementById(Xhtml).innerHTML+"\" value=\""+document.getElementById(Xihtml).value+"\"/>"+document.getElementById(Xihtml).value);
					//document.getElementById('transcript').value = document.getElementById('transcript').value.replace(/\<variable\>(\<\/variable\>)?/, document.getElementById(Xihtml).value+"\n");
					var thisvariable = new RegExp("<(X|x)>"+document.getElementById(Xhtml).innerHTML+"<\/(X|x)>","g");
					//document.getElementById('doc').innerHTML = document.getElementById('doc').innerHTML.replace(thisvariable, document.getElementById(document.getElementById(Xhtml).innerHTML).innerHTML);
					//document.getElementById('ondeck').innerHTML = document.getElementById('ondeck').innerHTML.replace(thisvariable, document.getElementById(valueis(currentQ)).innerHTML);
					//console.log("thisvariable: "+thisvariable);
					//console.log("Variable name: "+valueis(currentQ));
					//console.log("Variable value: "+document.getElementById(valueis(currentQ)).innerHTML);
					if(document.getElementById(Ahtml).innerHTML != "") { 
						//document.getElementById('transcript').value += "USER: "+document.getElementById(Xihtml).value+"\n"; 
						convo_bin.push("USER: "+document.getElementById(Xihtml).value+"\n");
					}
				} else {
					//document.getElementById('transcript').value += "USER: "+document.getElementById(Ahtml).innerHTML+"\n";
					convo_bin.push("USER: "+document.getElementById(Ahtml).innerHTML+"\n");
				}
				document.getElementById('Choices').innerHTML = '';
				if (goingback == 0) {
					setTimeout(function() {renderQnA(Qhtml,Jhtml,Dhtml,restart)}, 300);
				} else {
					renderQnA(Qhtml,Jhtml,Dhtml,restart);
				}
			} else {
				document.getElementById('Choices').innerHTML = '';
				path = [];
				renderQnA(Qhtml,Jhtml,Dhtml,restart);			
			}

		}
		
	}


	function renderQnA(Qht,Jht,Dht,restar) {
		Dhtml = Dht;
					
		GOTOfired = 0;
		path.push(label);

		swapGOTO(Qht,Jht);

		console.log("After swap: "+GOTOfired);

		if (GOTOfired == 0) {
			document.getElementById('QandA').innerHTML += "<div id="+Jht+" style=\"float:left;width:100%;height:1px;\"> </div>";
		}
		document.getElementById('QandA').innerHTML += "<div class='frame'><div class='full'><div class='question_text'>"+swapvar(document.getElementById(Qhtml).innerHTML)+"</div></div><div class='question_arrow'></div></div>";		

		document.getElementById('QandA').innerHTML = document.getElementById('QandA').innerHTML.replace(/(\<br\>){2}/gi,"</div></div><div class='question_arrow'></div></div></div></div><div class='frame'><div class='full'><div class='question_text'>");
		document.getElementById('QandA').innerHTML = document.getElementById('QandA').innerHTML.replace(/(\<br\> \<br\>)/gi,"<br><br>");

		// add question 
		//document.getElementById('transcript').value += swapvar("BOT: "+ document.getElementById(Qhtml).innerHTML);
		//document.getElementById('transcript').value = document.getElementById('transcript').value.replace(/(\<br\>){2}/gi,"\nBOT: ");
		this_text = swapvar("BOT: "+ document.getElementById(Qhtml).innerHTML);
		this_text = this_text.replace(/(\<br\>){2}/gi,"\nBOT: ");
		convo_bin.push(this_text);
				
		// make push doc into array in doc() cycle through array and put into output
		// maybe remove doc div
		if (document.getElementById(Dhtml)) {
			doc_bin.push([document.getElementById(Dhtml).innerHTML,currentQ]);
			console.log("Add to Doc ("+Dhtml+"): "+document.getElementById(Dhtml).innerHTML);
			//document.getElementById('doc').innerHTML += document.getElementById(Dhtml).innerHTML;
		}
						
		tmp = getElementsByIdRegExp("div", "A-"+label+"(\\.{1}\\d){1}$");
		a_href = getElementsByIdRegExp("div", "A-href-"+label+"(\\.{1}\\d){1}$");
		a_target = getElementsByIdRegExp("div", "A-target-"+label+"(\\.{1}\\d){1}$");
		tmp_x = getElementsByIdRegExp("div", "X-"+label+"(\\.{1}\\d){1}$");
		var Xishere = 0;
		for ( var i = 0; i < tmp.length; i++ ) {
			var nextlabel = tmp[i].id.substr(2);
			var Xihtml = 'Xi-'+nextlabel;
			var regexp = "\<variable\>";
			var regexp_js = "^javascript:";
			var script_call = "";
			if (tmp[i].innerHTML.match(regexp)) {
				if (a_href[i].innerHTML.match('^(_blank:)?javascript:')) {
					script_call = a_href[i].innerHTML.replace(/^(_blank:)?javascript:/gi,"");
				} else {
					if (a_href[i].innerHTML.match('^_blank:')) {
						script_call = "window.open('"+a_href[i].innerHTML.replace(/^_blank:/,"")+"','_blank');";			
					} else {
						script_call = "location.href = '"+a_href[i].innerHTML+"';";
					}
				}
				document.getElementById('Choices').innerHTML += "<div class=\"xdiv\"><input type=\""+a_target[i].innerHTML+"\" id=\""+Xihtml+"\" name=\""+Xihtml+"\" class=\"xinput\" onkeypress=\"if (event.keyCode==13){answerQ('"+nextlabel+"');"+script_call+"}\"/><a href=\"javascript:void('');\" class=\"xbutton\" onClick=\"answerQ('"+nextlabel+"');"+script_call+"\"><span class=\"qpad\">Save above text as answer.</span></a></div>";
				Xishere = Xihtml;
				freetext = Xihtml;
			} else if (a_href[i].innerHTML.match(regexp_js) && a_href[i].innerHTML != "javascript:void('');") {
				tmp[i].innerHTML = tmp[i].innerHTML.replace(/(\<br\>){2}/gi,"<br> <br>");
				var script_call = a_href[i].innerHTML.replace(/^javascript:/gi,"");
				document.getElementById('Choices').innerHTML += "<a href=\"javascript:void('');\" class=\"qabutton\" onClick=\"answerQ('"+nextlabel+"');"+script_call+"\" "+a_target[i].innerHTML+"><span class=\"qpad\">"+tmp[i].innerHTML+"</span></a>";							
				freetext = 0;
			} else {
				tmp[i].innerHTML = tmp[i].innerHTML.replace(/(\<br\>){2}/gi,"<br> <br>");
				document.getElementById('Choices').innerHTML += "<a href=\""+a_href[i].innerHTML+"\" class=\"qabutton\" onClick=\"answerQ('"+nextlabel+"');\" "+a_target[i].innerHTML+"><span class=\"qpad\">"+tmp[i].innerHTML+"</span></a>";				
				freetext = 0;
			}
		}			

		if (restar == undefined) {
			
			document.getElementById('Choices').innerHTML += "<div class=\"standard_buttons\">";
			if (QNum > 1) { 
				document.getElementById('Choices').innerHTML += "<a href=\"javascript:void('');\" class=\"sbutton\" onClick=\"goback(QNum);\">GO BACK ONE</a>";
				document.getElementById('Choices').innerHTML += "<a href=\"javascript:void('');\" class=\"sbutton\" style=\"float:right\" onClick=\"startAT('1');\">START OVER</a>";
			} else if (QNum == 1) {
				document.getElementById('Choices').innerHTML += "<a href=\"javascript:void('');\" class=\"sbutton\" onClick=\"startAT('1');\">GO BACK ONE</a>";
				document.getElementById('Choices').innerHTML += "<a href=\"javascript:void('');\" class=\"sbutton\" style=\"float:right\" onClick=\"startAT('1');\">START OVER</a>";				
			}
			document.getElementById('Choices').innerHTML += "</div>"
		}
				
		if (QNum != 0) { 
			if (goingback == 0) {
				scroll2Q(Jht,800);           	
			} else {
				window.scrollTo(0, document.getElementById(Jht).offsetTop);     		
			}
		} else if (restar != undefined) {
			window.scrollTo(0,0);
		}
		if (Xishere != 0 && window.self == window.top) {
			console.log("Set focus for: "+Xishere);
			document.getElementById(Xishere).focus();
		}
		console.log("Q#: "+QNum);
		console.log("New Path: "+path);
		QNum++;
		goingback = 0;
					
	}

	
	function swapGOTO(QH,JH) {
		var regex = new RegExp("GOTO:(\d*)(\.\d+)*");
		if (regex.test(document.getElementById(QH).innerHTML)) {
			var Qtext = document.getElementById(QH).innerHTML.match(/(GOTO:(\d*)(.\s*\d+)*)/);
			document.getElementById('QandA').innerHTML += "<div id="+JH+" style=\"float:left;width:100%;height:1px;\"> </div>";
			// Add question
			// note I added () around the < to avoid a < followed by a ? which causes problems in php
			var Qtexttrans = document.getElementById(QH).innerHTML.replace(/(<)?GOTO:(\d*)(.\s*\d+)*>?/,"");
			Qtexttrans = Qtexttrans.replace(/\s*$/,"");
			if (Qtexttrans != "") {
				//document.getElementById('transcript').value += swapvar("BOT: "+Qtexttrans+"\n");
				convo_bin.push(swapvar("BOT: "+Qtexttrans+"\n"));
			}
			if (document.getElementById(QH).innerHTML.match(/^GOTO:(\d*)(.\s*\d+)*/)) {
				document.getElementById('QandA').innerHTML += document.getElementById(QH).innerHTML.replace(/(<)?GOTO:(\d*)(.\s*\d+)*>?/,"<"+Qtext+">");
			} else {
				document.getElementById('QandA').innerHTML += "<div class='frame'><div class='full'><div class='question_text'>"+ swapvar(document.getElementById(QH).innerHTML.replace(/(<)?GOTO:(\d*)(.\s*\d+)*>?/,"<"+Qtext+">"))+"</div></div><div class='question_arrow'></div></div>";						
			}
			// replace GOTO with text
			label = Qtext[0].replace("GOTO:","");
			Qhtml = 'Q-'+label;
			if (document.getElementById(Dhtml)) {
				doc_bin.push([document.getElementById(Dhtml).innerHTML,currentQ]);
				console.log("Add to Doc ("+Dhtml+"): "+document.getElementById(Dhtml).innerHTML);
				//document.getElementById('doc').innerHTML += document.getElementById(Dhtml).innerHTML;
			}
			Dhtml = 'D-'+label;
			GOTOfired = 1;
			console.log("In swap: "+GOTOfired);
			swapGOTO(Qhtml,JH);
		}
	}

	
	function scroll2Q(id,speed) {
		var top = document.getElementById(id).offsetTop; //Getting Y of target element
		console.log("Jump to Y for ("+id+"): "+top);
		//adapted from https://github.com/Yappli/smooth-scroll
		var moving_frequency = 5; // Affects performance !
		var hop_count = speed/moving_frequency
        var getScrollTopDocumentAtBegin = document.documentElement.scrollTop + document.body.scrollTop;
        var gap = (top - getScrollTopDocumentAtBegin) / hop_count;
		for(var i = 1; i <= hop_count; i++)
        {
        	(function()
           	{
           		var hop_top_position = gap*i;
           	    setTimeout(function(){  window.scrollTo(0, hop_top_position + getScrollTopDocumentAtBegin); }, moving_frequency*i);
           	 })();
        }
	}

	function getElementsByIdIs(selectorTag, name) {
		var items = [];
		var myPosts = document.getElementsByTagName(selectorTag);
			//omitting undefined null check for brevity
			if (myPosts[0].id == name) {
				items.push(myPosts[0]);
			}
		
		return items;
	}

	function getElementsByIdRegExp(selectorTag, expression) {
		// note you need to escape \ in the expression with \, i.e., \\ = \
		var regex = new RegExp(expression);
		var items = [];
		var myPosts = document.getElementsByTagName(selectorTag);
		for (var i = 0; i < myPosts.length; i++) {
			if (regex.test(myPosts[i].id)) {
				items.push(myPosts[i]);
			}
		}
		
		return items;
	}	

	// startAT QnA
	function startAT(id) {
		document.getElementById('ondeck').innerHTML = document.getElementById('original').value;
		document.getElementById('QandA').innerHTML = "";
		//document.getElementById('transcript').value = "";
		doc_bin = [];
		convo_bin = [];
		QNum = 0;
		answerQ(id,'1');
	}
		
	//show funtion
	function show(id) { 
   		if (document.getElementById) { // DOM3 = IE5, NS6
        	document.getElementById(id).style.display = 'block';
    	} else { 
        	if (document.layers) {  
            	document.id.display = 'block';
        	} else {
                document.all.id.style.display = 'block';
        	}
    	}
	}

	//hide funtion
	function hide(id) { 
    	if (document.getElementById) { // DOM3 = IE5, NS6
        	document.getElementById(id).style.display = 'none';         
    	} else { 
        	if (document.layers) {  
                document.id.display = 'none';
        	} else {
                document.all.id.style.display = 'none';
        	}
    	}
	}

	//show OR hide funtion depends on if element is shown or hidden
	function shoh(id) { 
    	if (document.getElementById) { // DOM3 = IE5, NS6
        	if (document.getElementById(id).style.display == "none"){
            	document.getElementById(id).style.display = 'block';
        	} else {
            	document.getElementById(id).style.display = 'none';         
        	}   
    	} else { 
        	if (document.layers) {  
            	if (document.id.display == "none"){
                	document.id.display = 'block';
            	} else {
                	document.id.display = 'none';
            	}
        	} else {
            	if (document.all.id.style.visibility == "none"){
                	document.all.id.style.display = 'block';
            	} else {
                	document.all.id.style.display = 'none';
            	}
        	}
    	}
	}
	
	function swapvar(input) {
		var output; 
		for(var i = 0; i < QVnames.length; i++) {
			if (document.getElementById(QVnames[i][1])) {
				var item = QVnames[i][1].replace(/\./g,"\\.");
				var varegx = new RegExp("<x>"+item+"<\/x>","gi");
				//console.log(QVnames[i][1]);
				input = input.replace(varegx,document.getElementById(QVnames[i][1]).innerHTML);
			} 
		}
		output = input
		return output
	}
	
	function docforindex(indexID) {
		for(var i = 0; i < doc_bin.length; i++) {
			if(doc_bin[i][1] == indexID) {
				return true;
			}
		}
	}
	function indexis(variablename) {
		for(var i = 0; i < QVnames.length; i++) {
			if(QVnames[i][1] == variablename) {
				return QVnames[i][0];
			}
		}
	}
	function valueis(variablekey) {
		for(var i = 0; i < QVnames.length; i++) {
			if(QVnames[i][0] == variablekey) {
				return QVnames[i][1];
			}
		}
	}
	
	function look4goto(qn,id) {
		console.log("GOTO SEARCH: "+id);
		var qID = "Q-"+id;
		// If there's a doc in the XXXXXXXXXXXXXXXX, remove it.
		if (docforindex(path.indexOf(id))) {
			console.log("DOC FOUND "+id);
			doc_bin.splice(doc_bin.length-1,1);
		}
		convo_bin.splice(-2,2);
		var re = new RegExp("GOTO:(([a-z0-9\._-]*)\s*)$","gi");
		if (document.getElementById(qID).innerHTML.match(re)) {
			convo_bin.splice(-1,1);
			console.log("GOTO FOUND: "+id);
			textinput = re.exec(document.getElementById(qID).innerHTML)[2]+"";
			if (docforindex(indexis(textinput))) {
				document.getElementById("Xi-"+path[qn]).value = document.getElementById(valueis(textinput)).innerHTML;
				console.log("DOC FOUND "+textinput);
				doc_bin.splice(doc_bin.length-1,1);
			}
			look4goto(qn,textinput);
		}
	}
	
	function goback(qn) {
		Qlast = qn - 3
		qn = qn - 2;
		label = path[qn];
		goingback = 1;
		
		console.log("GO BACK TO:"+qn);
		var re = new RegExp('(((^|\\n).*)*)<div id="break-at-'+qn+'" class="frame">((.*)(\\W.*))*', 'g');
		document.getElementById("QandA").innerHTML = document.getElementById("QandA").innerHTML.replace(re, '$1');
		document.getElementById('Choices').innerHTML += "<input type=\"hidden\" id=\"Xi-"+path[qn]+"\" name=\"Xi-"+path[qn]+"\" value=\"\">";
			console.log("####################: "+path[path.length-1]);
		
		//look4goto(qn,path[path.length-1]);
		
		path.splice(-1,1);
		convo_bin.splice(-4,4);
		//convo_bin.splice(-2,2);

		// If there's a doc in the last Q that you're removing, hold on to it.
		// And put it back after you've removed it. When you rerender the Q.
		if (document.getElementById("X-"+path[qn]) && document.getElementById(valueis(path[Qlast]))) {
			document.getElementById("Xi-"+path[qn]).value = document.getElementById(valueis(path[Qlast])).innerHTML;
			doc_bin.splice(doc_bin.length-1,1);
		}
		
		// If there's a doc in the current Q, remove it.
		if (docforindex(currentQ)) {
			console.log("DOC FOUND (current) "+currentQ);
			doc_bin.splice(doc_bin.length-1,1);
		}
		// If there's a doc in the queued up Q, remove it. 
		if (document.getElementById(Dhtml)) {
			console.log("DOC FOUND (ondeck)"+Dhtml);
			doc_bin.splice(doc_bin.length-1,1);
		}
		
		look4goto(qn,path[path.length-1]);
		
		if (freetext != 0) {
			document.getElementById(freetext).value = "";
		}
		QNum = qn;
		loadQ = path[path.length-1];
		path.splice(-1,1);
		
		console.log("Reload ans for: "+loadQ);
		answerQ(loadQ);
	}

	function transcript(output) {
		var convo_output = "";
		for (var i = 0, len = convo_bin.length; i < len; i++) {
			convo_output += convo_bin[i];
		}
		if (output == 1) {
			return convo_output;
		} else {
			return convo_output.replace(/<[^>]*>/g,"");
		}
	}		
	
	function doc() {
		var doc_output = ""; 
		for (var i = 0, len = doc_bin.length; i < len; i++) {
			doc_output += doc_bin[i][0];
		}
		return swapvar(doc_output);
	}	
	
	function json_str() {
		
		var json_list = "{";
		for(var i = 0; i < QVnames.length; i++) {
			if (!document.getElementById("Q-"+QVnames[i][0]).innerHTML.match(/(GOTO:(\d*)(.\s*\d+)*)/)) {
				if (document.getElementById(QVnames[i][1])) {
					json_list = json_list+'"'+QVnames[i][1]+'":"'+document.getElementById(QVnames[i][1]).innerHTML+'"';
				} else {
					json_list = json_list+'"'+QVnames[i][1]+'":"'+'"';
				}
				json_list = json_list+",";
			} 
			if (i+1 == QVnames.length) {
				json_list = json_list.replace(/,$/, '');
				json_list = json_list+"}";
			}
		}
		return json_list;
	}

	function mail2(to,subject,body) {
		to = encodeURIComponent(to);
		subject = encodeURIComponent(subject);
		body = encodeURIComponent(body);
		window.location.href = "mailto:"+to+"?subject="+subject+"&body="+body;
	}
	
	function submit2(action,method,docAs,instructions,transcriptAs,jsonAs,target) {
		document.FORM.action = action;
		document.FORM.method = method;
		if (target) {
			document.FORM.target = target;
		} else {
			document.FORM.target = "_self";		
		}
		
		if (docAs) {
			var doctext = document.createElement("textarea");
			doctext.style.display ='none';
			doctext.name= docAs;
			doctext.value= doc();
			document.getElementById('FORM').appendChild(doctext);
			if (instructions) {
				var instructtext = document.createElement("textarea");
				instructtext.type='hidden';
				instructtext.style.display ='none';
				instructtext.name= 'i';
				instructtext.value= instructions;
				document.getElementById('FORM').appendChild(instructtext);	
			}
		}
		if (transcriptAs) {
			var ttext = document.createElement("textarea");
			ttext.type='hidden';
			ttext.style.display ='none';
			ttext.name= transcriptAs;
			ttext.value= transcript();
			document.getElementById('FORM').appendChild(ttext);
		}
		if (jsonAs) {
			var json = document.createElement("textarea");
			json.type='hidden';
			json.style.display ='none';
			json.name= jsonAs;
			json.value= json_str();
			document.getElementById('FORM').appendChild(json);
		}
		var ondeckdiv = document.getElementById('ondeck').innerHTML;
		var rawmarkupdiv = document.getElementById('rawmarkup').innerHTML;
		document.getElementById('ondeck').innerHTML = "";
		document.getElementById('rawmarkup').innerHTML = "";
		document.FORM.submit();
		document.getElementById('ondeck').innerHTML = ondeckdiv;
		document.getElementById('rawmarkup').innerHTML = rawmarkupdiv;
	}
	
	function csv() {
		var csv_list = "";
		for(var i = 0; i < QVnames.length; i++) {
			if (!document.getElementById("Q-"+QVnames[i][0]).innerHTML.match(/(GOTO:(\d*)(.\s*\d+)*)/)) {
				csv_list = csv_list+'"'+QVnames[i][1]+'"';
				csv_list = csv_list+",";
			} 
			if (i+1 == QVnames.length) {
				csv_list = csv_list.replace(/,$/, '');
				csv_list = csv_list+"\n";
			}
		}
		for(var i = 0; i < QVnames.length; i++) {
			if (!document.getElementById("Q-"+QVnames[i][0]).innerHTML.match(/(GOTO:(\d*)(.\s*\d+)*)/)) {
				if (document.getElementById(QVnames[i][1])) {
					csv_list = csv_list+'"'+document.getElementById(QVnames[i][1]).innerHTML+'"';
				} else {
					csv_list = csv_list+'""';
				}
				csv_list = csv_list+",";
			} 			
			if (i+1 == QVnames.length) {
				csv_list = csv_list.replace(/,$/, '');
				csv_list = csv_list+"\n";
			}
		}

		return csv_list;
	}
	
	function getvar(val) {
		return document.getElementById(val).value;
	}

	function goto(val) {
	   answerQ(indexis(val));
	}

	// h/t http://runnable.com/U5HC9xtufQpsu5aj/use-javascript-to-save-textarea-as-a-txt-file
	function save2(filename,content)
	{

	// I'm using file system support as a proxy for support for this feature. 
	// Check based on one found at: http://blog.teamtreehouse.com/building-an-html5-text-editor-with-the-filesystem-apis
	// Handle vendor prefixes.
	window.requestFileSystem = window.requestFileSystem || 
							   window.webkitRequestFileSystem;
	// Check for support.
	if (window.requestFileSystem) {
	// content = ID of textarea to save
	// name = name to save file as, including file extension     
	// grab the content of the form field and place it into a variable
	//    var textToWrite = document.getElementById(content).value;
	//  create a new Blob (html5 magic) that conatins the data from your form feild
		var textFileAsBlob = new Blob([content], {type:'text/plain'});
		
	// Specify the name of the file to be saved
		var fileNamecontentAs = filename;
		
	// Optionally allow the user to choose a file name by providing 
	// an imput field in the HTML and using the collected data here
	// var fileNamecontentAs = txtFileName.text;

	// create a link for our script to 'click'
		var downloadLink = document.createElement("a");
	//  supply the name of the file (from the var above).
	// you could create the name here but using a var
	// allows more flexability later.
		downloadLink.download = fileNamecontentAs;
	// provide text for the link. This will be hidden so you
	// can actually use anything you want.
		downloadLink.innerHTML = "My Hidden Link";
		
	// allow our code to work in webkit & Gecko based browsers
	// without the need for a if / else block.
		window.URL = window.URL || window.webkitURL;
			  
	// Create the link Object.
		downloadLink.href = window.URL.createObjectURL(textFileAsBlob);
	// when link is clicked call a function to remove it from
	// the DOM in case user wants to save a second file.
		downloadLink.onclick = destroyClickedElement;
	// make sure the link is hidden.
		downloadLink.style.display = "none";
	// add the link to the DOM
		document.body.appendChild(downloadLink);
		
	// click the new link
		downloadLink.click();
	} else {
		alert('This feature is not supported by your browser.');
	}
		
	}

	function destroyClickedElement(event)
	{
	// remove the link from the DOM
		document.body.removeChild(event.target);
	}

	// EOF

</script>

Q(1): Are you 18 years or older?
A: Yes.
	Q(1.1): I will provide a list of resources in the Boston area that you can utilize. What are you interested in?
	A(job training): Job Training
		Q(2.1): Pick the field you’re most interested in.
		A(construction): Construction
			Q(2.1.1): Here are some apprentice and training programs in the Greater Boston area. <br><br><a href="https://www.peoplesacademyinc.org">The Peoples Academy</a> <br><br><a href="https://buildingpathwaysboston.org/programs/">BuildingPathWays</a><br><br><a href="http://www.youthbuildboston.org/new-programs/">Youth Build</a>. 
			A: Thanks, I’m done with this.
				Q(2.1.1.1):GOTO:end
			A: I want to keep searching the resources.
				Q(2.1.1.2):GOTO:1.1
		A(food): Culinary Arts
			Q(2.1.2): <a href="https://ne-cat.org/culinary-arts-job-training/">NECAT</a><br><br><a href="http://bostonkroc.salvationarmy.org/BostonKroc/Culinary/">Kroc Center Culinary Arts Training Center</a> 
			A: Thanks, I’m done with this.
				Q(2.1.2.1):GOTO:end
			A: I want to keep searching the resources.
				Q(2.1.2.2):GOTO:1.1
		A(unsure): I’m unsure
			Q(2.1.3): Check out Boston’s career services program or Boston Public Health Commission’s Job Training/Education<br><br><a href="https://www.bostoncareerlink.org/index.php?option=com_content&view=article&id=1&Itemid=2/">Boston Career Link</a><br><br><a href="http://www.bphc.org/whatwedo/homelessness/homeless-services/Pages/Job-Training-and-Education.aspx/">Boston Public Health Commission</a>
			A: Thanks, I’m done with this.
				Q(2.1.3.1):GOTO:end
			A: I want to keep searching the resources.
				Q(2.1.3.2):GOTO:1.1
	A(Alternative education): Alternative Education
		Q(2.2): Are you interested in getting your HiSET, GED, or high school diploma?
		A: Yes
			Q(2.2.1): This hotline will help you figure the program that will benefit you the most! <a href="http://massliteracyhotline.org/hotline//">Massachusetts Literacy Hotline</a>
			A: Thanks, I’m done with this.
				Q(2.2.1.1):GOTO:end
			A: I want to keep searching the resources.
				Q(2.2.1.2):GOTO:1.1
		A: No.
			Q(2.2.2): Do you want to keep searching the resources?
			A: Yes please!
				Q(2.2.2.1):GOTO:1.1
			A: No thanks, I’m all set.
				Q(2.2.2.2):GOTO:end
	A(rehab): Rehabilitation Facility
		Q(2.3): Are you interested in participating in a program in Boston?
		A: Yes.
			Q(2.3.1): Here are a list of rehabilitation programs in Boston. <br><br> <a href="http://spauldingrehab.org/locations/spaulding-rehabilitation-hospital/">Spaulding</a><br><br><a href="http://www.bidmc.org/Centers-and-Departments/Departments/Patient-And-Family-Care-Services/Rehabilitation-Services/Inpatient-Rehabilitation-Services.aspx/">Beth Israel Deaconess Medical Center</a><br><br><a href="http://www.hebrewseniorlife.org/rehab-services-boston/">Hebrew Rehabilitation Center</a>
			A: Thanks, I’m done with this.
				Q(2.3.1.1):GOTO:end
			A: I want to keep searching the resources.
				Q(2.3.1.2):GOTO:1.1
		A: No. 
			Q(2.3.2): Unfortunately, this QnA is only focused on the Boston area. Do you want to keep searching for programs?
			A: Yes.
				Q(2.3.2.1):GOTO:1.1
			A: No.
				Q(2.3.2.2):GOTO:end
	A(community): Community Service
		Q(2.4): Are you interested in or in need of completing community service in the Boston area?
		A: Yes.
			Q(2.4.1): Here are list of programs in need of volunteers. <br><br><a href="http://bostonkroc.salvationarmy.org/">Kroc Center</a><br><br><a href="http://www.pinestreetinn.org/">Pine St. Inn</a><br><br><a href="https://www.foodpantries.org/ci/ma-boston/">Food Pantries</a><br><br><a href="https://www.bostoncares.org/">Boston Cares</a>
			A: Thanks, I’m done with this.
				Q(2.4.1.1):GOTO:end
			A: I want to keep searching the resources.
				Q(2.4.1.2):GOTO:1.1
		A: No, I want to complete it outside of Boston.
			Q(2.4.2): Unfortunately, this QnA only focuses on the Boston area. Do you want to keep searching for programs?
			A: Yes.
				Q(2.4.2.1):GOTO:1.1
			A: No.
				Q(2.4.2.2):GOTO:end
	A(health): Health Clinic
		Q(2.5): Here are a list of judgment-free clinics. <br><br><a href="http://sidneyborum.org/care/">Sidney Borum Clinic</a><br><br><a href=http://www.bphc.org/whatwedo/homelessness/homeless-services/Pages/locations.aspx/>Woods Mullen Shelter</a>
		A: Thanks, I’m done with this.
			Q(2.5.1.1):GOTO:end
		A: I want to keep searching the resources.
			Q(2.5.1.2):GOTO:1.1
	A(all set): I am done searching.
		Q(2.6):GOTO:end
A: No.
	Q(1.2):GOTO:2
Q(2): If you are looking for juvenile services, please use Nicole Siino’s website application for available juvenile resources.
Q(end): Thank you for participating!

