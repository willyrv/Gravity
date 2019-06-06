---
layout: default
title: programme
permalink: /programme/
tagline: ""
---

<script type="text/javascript">
function hideStuff(id) {
    // hide the element
    document.getElementById(id).style.display = 'none';

}

function showStuff(id) {
    // show the lorem ipsum text
    document.getElementById(id).style.display = 'block';

}

</script>


<script type="text/javascript">
    // Initialize Variables
    var closePopup = document.getElementById("popupclose");
    var overlay = document.getElementById("overlay");
    var popup = document.getElementById("popup");
    var button = document.getElementById("button");
    // Close Popup Event
    closePopup.onclick = function() {
        overlay.style.display = 'none';
        popup.style.display = 'none';
    };
    // Show Overlay and Popup
    function showPopup(id1, id2){
	document.getElementById(id1).style.display = 'block';
	document.getElementById(id2).style.display = 'block';
    }
    function hidePopup(id1, id2){
	document.getElementById(id1).style.display = 'none';
	document.getElementById(id2).style.display = 'none';
    }
</script>

<style>

.tableheader{
  background: #D5D5D5;
  height: 50px;
  font-size: 20px;
}

.tablerow{
  background: #FAFAFA;
  height: 70px;
}

.timedetails{
  width: 180px;
  text-align: center;
}



#overlay {
    display: none;
    position: absolute;
    top: 0;
    bottom: 0;
    background: #999;
    width: 100%;
    height: 100%;
    opacity: 0.8;
    z-index: 100;
}
.popup {
    display: none;
    position: fixed;
    top: 50%;
    left: 50%;
    background: #D3EFED;
    margin-left: -400px; /*Half the value of width to center div*/
    margin-top: -250px; /*Half the value of height to center div*/
    z-index: 200;
}
.popupclose {
    float: right;
    padding: 10px;
    cursor: pointer;
}
.popupcontent {
    padding: 10px;
    width: 700px;
    height: 400px;
    overflow-y: auto;
}
.popupcontrols{
    height: 30px;
    background: #8BBCCF;
}
#button {
    cursor: pointer;
}

</style>

<br/>

<table id="schedule" style="border-collapse: collapse;">
   <thead>
      <tr class="tableheader">
         <th colspan="2">Programme</th>
      </tr>
   </thead>
   <tbody>
      <tr class="tablerow">
         <td class="timedetails">DAY 1<br/> Thu, 20<sup>th</sup> Jun.</td>
         <td></td>
      </tr>
      <tr class="tablerow">
         <td class="timedetails">08:30 - 09:00</td>
         <td>INTRO: <u>Olivier Mazet</u> and <u>Lounès Chikhi</u> <br/> <i>Why models are important: population genetics and beyond.</i></td>
      </tr>
      <tr class="tablerow">
         <td class="timedetails">09:00 - 10:00</td>
         <td><u>Jérôme Chave </u>. <br/><i>Why individual-based models are important to understand ecosystems?</i>  <br> <span onclick="showPopup('popupRasmus', 'popupcloseRasmus'); return false;" style="cursor: pointer;">(view abstract)</span>
         <div id="popupRasmus" class="popup">
    <div class="popupcontrols">
        <span id="popupcloseRasmus" onclick="hidePopup('popupRasmus', 'popupcloseRasmus'); return false;" class="popupclose">x</span>
    </div>
    <div class="popupcontent">
		Abstract to be announced         
    </div>
    </div>
         </td>
      </tr>
    <tr class="tablerow">
         <td class="timedetails">10:00 - 10:30</td>
         <td> COFFEE BREAK
         </td>
      </tr>
      <tr class="tablerow">
         <td class="timedetails">10:30 - 11:30</td>
         <td><u>Claudine Chaouiya </u>. <br/><i>Modelling molecular networks to assess relevant static and dynamical properties</i>  <br> <span onclick="showPopup('popupRasmus', 'popupcloseRasmus'); return false;" style="cursor: pointer;">(view abstract)</span>
         <div id="popupRasmus" class="popup">
    <div class="popupcontrols">
        <span id="popupcloseRasmus" onclick="hidePopup('popupRasmus', 'popupcloseRasmus'); return false;" class="popupclose">x</span>
    </div>
    <div class="popupcontent">
		Abstract to be announced         
    </div>
    </div>
         </td>
      </tr>
    <tr class="tablerow">
         <td class="timedetails">11:30 - 12:00</td>
         <td> PAUSE / DISCUSSION
         </td>
      </tr>      
    <tr class="tablerow">
         <td class="timedetails">12:00 - 14:00</td>
         <td> LUNCH
         </td>
      </tr>        
      <tr class="tablerow">
         <td class="timedetails">14:00 - 15:00</td>
         <td><u>Claire de Mazencourt </u>. <br/><i>Biodiversity, ecosystem functioning & stability: theory & modelling</i>  <br> <span onclick="showPopup('popupRasmus', 'popupcloseRasmus'); return false;" style="cursor: pointer;">(view abstract)</span>
         <div id="popupRasmus" class="popup">
    <div class="popupcontrols">
        <span id="popupcloseRasmus" onclick="hidePopup('popupRasmus', 'popupcloseRasmus'); return false;" class="popupclose">x</span>
    </div>
    <div class="popupcontent">
		Abstract to be announced         
    </div>
    </div>
         </td>
      </tr>
      <tr class="tablerow">
         <td class="timedetails">15:00 - 16:00</td>
         <td><u>Erida Gjini </u>. <br/><i>Understanding microbial competition with mathematical models</i>  <br> <span onclick="showPopup('popupRasmus', 'popupcloseRasmus'); return false;" style="cursor: pointer;">(view abstract)</span>
         <div id="popupRasmus" class="popup">
    <div class="popupcontrols">
        <span id="popupcloseRasmus" onclick="hidePopup('popupRasmus', 'popupcloseRasmus'); return false;" class="popupclose">x</span>
    </div>
    <div class="popupcontent">
		Abstract to be announced         
    </div>
    </div>
         </td>
      </tr>
    <tr class="tablerow">
         <td class="timedetails">16:00 - 16:30</td>
         <td> COFFEE BREAK
         </td>
      </tr>
      <tr class="tablerow">
         <td class="timedetails">16:30 - 17:30</td>
         <td><u>Robin Aguilée </u>. <br/><i>How to use models to link microevolutionary mechanisms and macroevolutionary patterns?</i>  <br> <span onclick="showPopup('popupRasmus', 'popupcloseRasmus'); return false;" style="cursor: pointer;">(view abstract)</span>
         <div id="popupRasmus" class="popup">
    <div class="popupcontrols">
        <span id="popupcloseRasmus" onclick="hidePopup('popupRasmus', 'popupcloseRasmus'); return false;" class="popupclose">x</span>
    </div>
    <div class="popupcontent">
		Abstract to be announced         
    </div>
    </div>
         </td>
      </tr>
    <tr class="tablerow">
         <td class="timedetails">17:30 - 18:00</td>
         <td> PAUSE / DISCUSSION
         </td>
      </tr>
      <tr class="tablerow">
         <td class="timedetails">18:00 - 19:00</td>
         <td>Keynote: <u>António Coutinho</u>. <br/><i>Models and immunology: a personal and historical account</i>  <br> <span onclick="showPopup('popupRasmus', 'popupcloseRasmus'); return false;" style="cursor: pointer;">(view abstract)</span>
         <div id="popupRasmus" class="popup">
    <div class="popupcontrols">
        <span id="popupcloseRasmus" onclick="hidePopup('popupRasmus', 'popupcloseRasmus'); return false;" class="popupclose">x</span>
    </div>
    <div class="popupcontent">
		Abstract to be announced         
    </div>
    </div>
         </td>
      </tr>
      <tr class="tablerow">
         <td class="timedetails">DAY 2<br/> Fri, 21<sup>th</sup> Jun.</td>
         <td></td>
      </tr>
      <tr class="tablerow">
         <td class="timedetails">08:30 - 09:00</td>
         <td></td>
      </tr>
      <tr class="tablerow">
         <td class="timedetails">09:00 - 10:00</td>
         <td>Keynote: <u>Paul Antoine Miquel</u>. <br/><i>Gaia and Solaris</i>  <br> <span onclick="showPopup('popupRasmus', 'popupcloseRasmus'); return false;" style="cursor: pointer;">(view abstract)</span>
         <div id="popupRasmus" class="popup">
    <div class="popupcontrols">
        <span id="popupcloseRasmus" onclick="hidePopup('popupRasmus', 'popupcloseRasmus'); return false;" class="popupclose">x</span>
    </div>
    <div class="popupcontent">
		Abstract to be announced         
    </div>
    </div>
         </td>
      </tr>
    <tr class="tablerow">
         <td class="timedetails">10:00 - 10:30</td>
         <td> COFFEE BREAK
         </td>
      </tr>
      <tr class="tablerow">
         <td class="timedetails">10:30 - 11:30</td>
         <td><u>Jorge Carneiro</u>. <br/><i>Collective and individual decision making by cells: analogies, simulations and models</i>  <br> <span onclick="showPopup('popupRasmus', 'popupcloseRasmus'); return false;" style="cursor: pointer;">(view abstract)</span>
         <div id="popupRasmus" class="popup">
    <div class="popupcontrols">
        <span id="popupcloseRasmus" onclick="hidePopup('popupRasmus', 'popupcloseRasmus'); return false;" class="popupclose">x</span>
    </div>
    <div class="popupcontent">
		Abstract to be announced         
    </div>
    </div>
         </td>
      </tr>
    <tr class="tablerow">
         <td class="timedetails">11:30 - 12:00</td>
         <td> PAUSE / DISCUSSION
         </td>
      </tr>      
    <tr class="tablerow">
         <td class="timedetails">12:00 - 14:00</td>
         <td> LUNCH
         </td>
      </tr>        
      <tr class="tablerow">
         <td class="timedetails">14:00 - 15:00</td>
         <td><u>Arnaud Pocheville </u>. <br/><i>TBA</i>  <br> <span onclick="showPopup('popupRasmus', 'popupcloseRasmus'); return false;" style="cursor: pointer;">(view abstract)</span>
         <div id="popupRasmus" class="popup">
    <div class="popupcontrols">
        <span id="popupcloseRasmus" onclick="hidePopup('popupRasmus', 'popupcloseRasmus'); return false;" class="popupclose">x</span>
    </div>
    <div class="popupcontent">
		Abstract to be announced         
    </div>
    </div>
         </td>
      </tr>
      <tr class="tablerow">
         <td class="timedetails">15:00 - 16:00</td>
         <td><u>Alekos Athanasiadis</u>. <br/><i>TBA</i>  <br> <span onclick="showPopup('popupRasmus', 'popupcloseRasmus'); return false;" style="cursor: pointer;">(view abstract)</span>
         <div id="popupRasmus" class="popup">
    <div class="popupcontrols">
        <span id="popupcloseRasmus" onclick="hidePopup('popupRasmus', 'popupcloseRasmus'); return false;" class="popupclose">x</span>
    </div>
    <div class="popupcontent">
		Abstract to be announced         
    </div>
    </div>
         </td>
      </tr>
    <tr class="tablerow">
         <td class="timedetails">16:00 - 16:30</td>
         <td> COFFEE BREAK
         </td>
      </tr>
      <tr class="tablerow">
         <td class="timedetails">16:30 - 17:30</td>
         <td><u>Lounes Chikhi</u> and <u>Olivier Mazet</u>. <br/><i>Panmixia versus structure: why it changes how we can view human origins</i>  <br> <span onclick="showPopup('popupRasmus', 'popupcloseRasmus'); return false;" style="cursor: pointer;">(view abstract)</span>
         <div id="popupRasmus" class="popup">
    <div class="popupcontrols">
        <span id="popupcloseRasmus" onclick="hidePopup('popupRasmus', 'popupcloseRasmus'); return false;" class="popupclose">x</span>
    </div>
    <div class="popupcontent">
		Abstract to be announced         
    </div>
    </div>
         </td>
      </tr>
    <tr class="tablerow">
         <td class="timedetails">17:30 - 18:00</td>
         <td> PAUSE / DISCUSSION
         </td>
      </tr>
      <tr class="tablerow">
         <td class="timedetails">18:00 - 19:00</td>
         <td>Keynote: <u>Giuseppe Longo</u>. <br/><i>Models vs Imitations. Geometric schemata for biological time</i>  <br> <span onclick="showPopup('popupRasmus', 'popupcloseRasmus'); return false;" style="cursor: pointer;">(view abstract)</span>
         <div id="popupRasmus" class="popup">
    <div class="popupcontrols">
        <span id="popupcloseRasmus" onclick="hidePopup('popupRasmus', 'popupcloseRasmus'); return false;" class="popupclose">x</span>
    </div>
    <div class="popupcontent">
		Abstract to be announced         
    </div>
    </div>
         </td>
      </tr>             
    </tbody>
</table>

<br/>
