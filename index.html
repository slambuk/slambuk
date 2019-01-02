<!DOCTYPE html>
<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/crypto-js/3.1.2/rollups/aes.js"></script>
<script>

//localStorage.removeItem("questions");

function createlink(){
	document.getElementById("dispques").innerHTML = '';
	
	var ques = [];
	ques[0] = document.getElementById("q1").value;
	ques[1] = document.getElementById("q2").value;
	ques[2] = document.getElementById("q3").value;
	ques[3] = document.getElementById("q4").value;
	ques[4] = document.getElementById("q5").value;
	ques[5] = document.getElementById("name").value;
	localStorage.setItem("questions", JSON.stringify(ques));
	
	var storedques = JSON.parse(localStorage.getItem("questions"));
	$("#dispques").append('<h2>Your questions are :</h2>');
	for (var i=0; i<storedques.length; i++){	
		$("#dispques").append(storedques[i]+'<br>');
	}
	
	var param = JSON.stringify(ques);
	//param = 'blah blah blah';
	var encrypted = CryptoJS.AES.encrypt(param, "7044015977");
	//var encrypted2 = CryptoJS.AES.encrypt(encrypted.toString(CryptoJS.enc.Utf8), "9433211656");
	//var decrypted2 = CryptoJS.AES.decrypt(encrypted2, "9433211656");
	var decrypted = CryptoJS.AES.decrypt(encrypted, "7044015977");
	$("#dispques").append('<br>'+param+'<br>'+encrypted+'<br>'+decrypted.toString(CryptoJS.enc.Utf8)+'<br>'+param);
	//document.getElementById("dispques").innerHTML = decrypted;
	
	document.getElementById("link").href = 'urlparse.html?q='+encrypted;
	document.getElementById("copylink").innerHTML = 'https://custrd.github.io/custrd/urlparse.html?q='+encrypted;
	document.getElementById("linkdiv").style.display = 'block';
		
	shorturl();
}

</script>
</head>
<body>
<div>

<p>question 1 : <textarea id='q1' placeholder='question 1' name='ques1' ></textarea></p>
<p>question 2 : <textarea id='q2' placeholder='question 2' name='ques2' ></textarea></p>
<p>question 3 : <textarea id='q3' placeholder='question 3' name='ques3' ></textarea></p>
<p>question 4 : <textarea id='q4' placeholder='question 4' name='ques4' ></textarea></p>
<p>question 5 : <textarea id='q5' placeholder='question 5' name='ques5' ></textarea></p>
<p>Your full name or instagram username : <input type='text' id='name' placeholder='enter your name' /></p>
<p><input onclick='createlink()' type='button' name='addques' value='create link' /></p>

</div>

<div id='linkdiv' style='display:none;'>
<div id='dispques' ></div>

<div id='displink' >
<br><label id='copylink' ></label><br>
<a id='link' href='' >click</a>
<br>
</div>

<div ><input type='text' id='surl' value='' placeholder='shareable link' ><button onclick='copytext()'>copy link</button></div>
<!--<div><label id='surl' ></label><button onclick='copytext()'>copy link</button></div>-->
</div>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script src="urlshorten.js"></script>
</body>
<script>

if (localStorage.getItem("questions") != null) {
	var storedques = JSON.parse(localStorage.getItem("questions"));
	document.getElementById("q1").value = storedques[0];
	document.getElementById("q2").value = storedques[1];
	document.getElementById("q3").value = storedques[2];
	document.getElementById("q4").value = storedques[3];
	document.getElementById("q5").value = storedques[4];
	document.getElementById("name").value = storedques[5];
}

function copytext() {
  var copyText = document.getElementById("surl");
  copyText.select();
  document.execCommand("copy");
}

</script>
</html>
