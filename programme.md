---
layout: default
title: programme
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
    background: #ededed;
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
    background: #d2d1d3;
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
         <td class="timedetails"><strong>DAY 1<br/> Thu, 20<sup>th</sup> Jun.</strong></td>
         <td></td>
      </tr>
      <tr class="tablerow">
         <td class="timedetails">08:30 - 09:00</td>
         <td>INTRO: <u>Olivier Mazet</u> and <u>Lounès Chikhi</u> <br/> <i>Why models are important: population genetics and beyond.</i><br> <span onclick="showPopup('popupRasmus', 'popupcloseRasmus'); return false;" style="cursor: pointer;">(view abstract)</span>
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
         <td><u>Claudine Chaouiya </u>. <br/><i>Modelling molecular networks to assess relevant static and dynamical properties</i>  <br> <span onclick="showPopup('popupCChaouiya', 'popupcloseCChaouiya'); return false;" style="cursor: pointer;">(view abstract)</span>
         <div id="popupCChaouiya" class="popup">
    <div class="popupcontrols">
        <span id="popupcloseCChaouiya" onclick="hidePopup('popupCChaouiya', 'popupcloseCChaouiya'); return false;" class="popupclose">x</span>
    </div>
    <div class="popupcontent">
		Heterogeneous and complex molecular networks control cellular processes. While tremendous technical progresses led to the identification of molecular interactions, computational modelling is required to make sense of these data. I will first discuss the notion of molecular networks, the variety of related semantics, and provide a short overview of modelling approaches. I will then focus on the notion of (discrete) dynamical systems, on different types of properties and their biological relevance.
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
         <td><u>Claire de Mazancourt </u>. <br/><i>Biodiversity, ecosystem functioning & stability: theory & modelling</i>  <br> <span onclick="showPopup('popupCMazancourt', 'CMazancourt'); return false;" style="cursor: pointer;">(view abstract)</span>
         <div id="popupCMazancourt" class="popup">
    <div class="popupcontrols">
        <span id="popupcloseCMazancourt" onclick="hidePopup('popupCMazancourt', 'CMazancourt'); return false;" class="popupclose">x</span>
    </div>
    <div class="popupcontent">
		How mathematical models link with experimental data, with inputs from mathematics and physics to help us understand how biodiversity affects ecosystem functioning & stability. I’ll outline some of the research carried at the Centre for Biodiversity Theory and Modelling in Moulis.
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
         <td class="timedetails">18:00 - 19:00</td>
         <td>Keynote: <u>Giuseppe Longo</u>. <br/><i>Models vs Imitations. Geometric schemata for biological time</i>  <br> <span onclick="showPopup('popupGLongo', 'popupcloseGLongo'); return false;" style="cursor: pointer;">(view abstract)</span>
         <div id="popupGLongo" class="popup">
    <div class="popupcontrols">
        <span id="popupcloseGLongo" onclick="hidePopup('popupGLongo', 'popupcloseGLongo'); return false;" class="popupclose">x</span>
    </div>
    <div class="popupcontent">
        In his 1950, Turing proposed an "imitation game". The idea was to fool a person who, by asking questions via a teleprinter, seeks to establish whether the respondent is a woman or a machine. In no way Turing tried by this to find out how a human brain works, or to make a mathematical model of the brain. Turing's 1952 paper on morphogenesis, instead, describes a model of an action/ reaction/diffusion (non-)linear system that may allow to understand the genesis of (bio-chemical) forms. Can this help to understand today the differences between phenomenological modeling, analytic and computational simulations ? The proposal of (geometric) ''schemata'' is yet another use of mathematical tools for intelligibility which allowed us to de-spacialise biological time, in contrast to the prevailing physical modeling of time, increasingly identified with or subordinated to space, from Aristotle to Galileo and Einstein.
        <br/>

        <strong>References</strong> <br/>
        - https://www.di.ens.fr/users/longo/download.html:<br/>G. Longo.  Letter to Alan Turing.  Invited, in Theory, Culture and Society, Posthumanities Special Issue, 2018 <br/>
        - https://www.di.ens.fr/users/longo/files/Letter-to-Turing.pdf Francis Bailly, Giuseppe Longo, Maël Montévil.    A 2-dimensional Geometry for Biological Time.  In Progress in Biophysics and Molecular Biology: vol. 106, n. 3, pp. 474 – 484, 2011 <br/>
        - https://www.di.ens.fr/users/longo/files/CIM/2-dimTime.pdf
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
         <td class="timedetails"><strong>DAY 2<br/> Fri, 21<sup>th</sup> Jun.</strong></td>
         <td></td>
      </tr>
      <tr class="tablerow">
         <td class="timedetails">09:00 - 10:00</td>
         <td>Keynote: <u>Paul Antoine Miquel</u>. <br/><i>Gaia and Solaris</i>  <br> <span onclick="showPopup('popupPAMiquel', 'popupclosePAMiquel'); return false;" style="cursor: pointer;">(view abstract)</span>
         <div id="popupPAMiquel" class="popup">
    <div class="popupcontrols">
        <span id="popupclosePAMiquel" onclick="hidePopup('popupPAMiquel', 'popupclosePAMiquel'); return false;" class="popupclose">x</span>
    </div>
    <div class="popupcontent">
		This presentation is focused on the relation between a novel of Stanislas Lem, Solaris, and the work of the geochemist James Lovelock. Behind the strong differences between a fiction based on the rule of suspension of disbelief, and a scientific assumption compatible with the rule of truth, we will show Gaia and Solaris are based on two common philosophical statements: life must be understood, not simply at the level of the organism, but also at the level of the biosphere; and life is some kind of primitive mind without any intentional purpose, and then without consciousness. Gaia knows how to proceed in order to regulate geochemical conditions that permit its own existence, even if it cannot know that it has this ability and this skill.         
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
         <td><u>Arnaud Pocheville </u>. <br/><i>On virtues of modelling in biology</i>  <br> <span onclick="showPopup('popupAPocheville', 'popupcloseAPocheville'); return false;" style="cursor: pointer;">(view abstract)</span>
         <div id="popupAPocheville" class="popup">
    <div class="popupcontrols">
        <span id="popupcloseAPocheville" onclick="hidePopup('popupAPocheville', 'popupcloseAPocheville'); return false;" class="popupclose">x</span>
    </div>
    <div class="popupcontent">
		Models in biology are notoriously false. This property of models raises a subtle philosophical question: how can models be scientifically virtuous, in spite of being false? Or, rather, aren't models virtuous thanks to their being false?
    </div>
    </div>
         </td>
      </tr>
      <tr class="tablerow">
         <td class="timedetails">16:30 - 17:30</td>
         <td><u>Robin Aguilée </u>. <br/><i>How to use models to link microevolutionary mechanisms and macroevolutionary dynamics?</i>  <br> <span onclick="showPopup('popupRobinAguilee', 'popupcloseRobinAguilee'); return false;" style="cursor: pointer;">(view abstract)</span>
         <div id="popupRobinAguilee" class="popup">
    <div class="popupcontrols">
        <span id="popupcloseRobinAguilee" onclick="hidePopup('popupRobinAguilee', 'popupcloseRobinAguilee'); return false;" class="popupclose">x</span>
    </div>
    <div class="popupcontent">
        Macroevolutionary patterns (e.g. rate of diversification, species-area relationship) ultimately result from microevolutionary mechanisms (competition, trait evolution, etc.). Nevertheless, the causal links between micro- and macro-timescales are usually very difficult to establish from empirical patterns. This explains why many macroevolutionary studies suggest historical scenarios compatible with the observed current patterns but do not prove that it is indeed what happened. I will discuss how models can be used to mechanistically link micro- and macroevolution. I will discuss how far such explicit link allows to establish causal relationships between microevolutionary processes and macroevolutionary patterns. I will illustrate the discussion with an individual-based model of diversification combining ecological, genetic and geographical causes of speciation and extinction, and producing macroevolutionary outputs such as phylogenetic trees.          
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
         <td><u>Lounes Chikhi</u> and <u>Olivier Mazet</u>. <br/><i>Panmixia versus structure: genomic data and recent human evolution</i>  <br> <span onclick="showPopup('popupLounes_Mazet', 'popupcloseLounes_Mazet'); return false;" style="cursor: pointer;">(view abstract)</span>
         <div id="popupLounes_Mazet" class="popup">
    <div class="popupcontrols">
        <span id="popupcloseLounes_Mazet" onclick="hidePopup('popupLounes_Mazet', 'popupcloseLounes_Mazet'); return false;" class="popupclose">x</span>
    </div>
    <div class="popupcontent">
		Genetic and genomic data are increasingly used to reconstruct the demographic history of species. Some studies suggest that humans went through a bottleneck and expansions. Others claim that (some) humans admixed with Neanderthals. The aim of this talk is to try and discuss how the assumptions made (or the models used) by different authors may lead them to make (very different) statements on the evolution of humans, on the basis of genomic data. We will discuss in particular the importance of models that incorporate structure (the fact that mating is geographically constrained) and models that ignore structure (i.e. assume that population structure can be ignored for some inference). In a period where some studies are questioning the scenario whereby humans evolved in Africa, it is important to understand what genetic data allow to say and what they cannot allow us to say.
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
         <td class="timedetails">10:30 - 11:30</td>
         <td>Keynote: <u>To Be Announced</u>. <br/><i>TBA</i>  <br> <span onclick="showPopup('popupRasmus', 'popupcloseRasmus'); return false;" style="cursor: pointer;">(view abstract)</span>
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
