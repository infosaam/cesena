# Sala di Cesena

<div>   
<button type="button" class="collapsible active">+ Orario lezioni</button>
<div class="content" style="display: none;" markdown="1">

- Martedì: ore 20.30 - 23.00
- Giovedì: ore 20.45 - 23.00
</div>
</div>

<div>   
<button type="button" class="collapsible active">+ Indirizzo palestra</button>
<div class="content" style="display: none;" markdown="1">

Via Boscone, 200, 47521 Cesena FC
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d721.7156826055801!2d12.256750031566366!3d44.14984244308505!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x132ca4b58a2ab9c7%3A0x9aa3a2a5ba1a60e6!2sSala%20d&#39;Arme%20Achille%20Marozzo%20sede%20di%20Cesena%20-%20Corsi%20di%20Scherma%20Medievale%20e%20Antica!5e1!3m2!1sen!2sit!4v1677516586613!5m2!1sen!2sit" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
</div>
</div>

<script type="text/javascript">

    function loadCSS(filename){ 

       var file = document.createElement("link");
       file.setAttribute("rel", "stylesheet");
       file.setAttribute("type", "text/css");
       file.setAttribute("href", filename);
       document.head.appendChild(file);
    }

    //just call a function to load your CSS
    //this path should be relative your HTML location
    loadCSS("collapse.css");

    var coll = document.getElementsByClassName("collapsible");
    var i;

    for (i = 0; i < coll.length; i++) {
      coll[i].addEventListener("click", function() {
        this.classList.toggle("active");
        var content = this.nextElementSibling;
        if (content.style.display === "block") {
          content.style.display = "none";
        } else {
          content.style.display = "block";
        }
      });
    }

</script>
