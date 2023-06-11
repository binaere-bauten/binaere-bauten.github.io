<script >
    import SolutionItem from "./solutionItem.svelte";

</script>


<div id = content>

    <h1>Binäre Bauten </h1>

    
    <h2>Beratungshaus und Software-Entwicklung im Herzen Berlins. </h2>

    <div class=text>

        <p>Als Firma im Jahr 2008 ins Geschäftsleben gestellt von einem Team hochqualifizierter Informatiker fokussieren wir uns auf die Felder Softwarearchitektur, Refaktorierung und Projektverantwortung.</p>
        <p>Trotz komplexer und vielfältig anwendbarer Spezialgebiete sind wir uns mit unseren Kunden einig im Verständnis, dass Klarheit und Schlichtheit erstrebenswerte, aber oft vernachlässigte Qualitätsmerkmale sind.</p>
        <p>Unsere Erfahrungen haben wir uns in der Vergangenheit individuell und wiederholt auch gemeinsam in unterschiedlichsten Projektsituationen und -positionen im Auftrag namhafter [und genauso auch wenig bekannter, aber deswegen nicht minder einflussreicher, stilbildender oder fordernder] Softwareproduzenten erarbeitet.</p>
        <p>Neben Kompetenz und Erfahrung sehen wir in Kommunikation, Agilität und interdisziplinärem Interesse die Schlüssel zu erfolgreicher Projektarbeit.</p>

        <!-- <div class=text_end></div> -->
    </div>  

    <div style="padding-bottom:4em"></div>

    <p class=title>unsere Lösungen:</p>


        <div class=solutions>

            <SolutionItem title="Quecksolver" description="Excel arbeit im Team koordinieren."/>

            <SolutionItem title="Development" description="Softwareentwicklung mit Fokus auf Architektur und Refaktorierung."/>
            <SolutionItem title="Beratung" description="Beratung mit Fokus auf Architektur und Refaktorierung."/>
            <SolutionItem title="Instandhaltung" description="Instandhaltung mit Fokus auf Architektur und Refaktorierung."/>

        </div>
        



</div>


<style>

    .title{
        font-size: 20px;
        font-weight: bold;
        /* margin-left:7vh; */
        margin-top:2em;
        background-color: var(--blue);
        color:white;
        display: initial;
        padding: .2em 1em;
    }

    .solutions{
        display: flex;
        flex-direction: row;
        justify-content:left;
        align-items: left;
        flex-wrap: wrap;
        padding-left:7vh;
        padding-top:2em;
    }


</style>


