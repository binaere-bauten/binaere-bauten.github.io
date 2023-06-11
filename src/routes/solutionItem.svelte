

<script lang='ts'>
    export var title:string
    export var description:string

</script>

<div class=solution>

    <a  href="products">

        <div class=display >
            <h3>{title}</h3>
            
            <p>{description}</p>
        </div>
    </a>

</div>


<style>

    .solution{

        font-size: 20px;
        width: 18em;
        height: 12em;
        /* border: 1px solid black; */

        justify-content: center;
        align-items: center;


        transition: 0.2s ease-in-out;
        cursor: pointer;


    }

    .display{
        /* border: 1px solid black; */
        box-shadow: 0px 0px 1em 0px rgba(0, 0, 0, 0.161);
        width: 14em;
        height: 8em;
        margin:auto;
        margin-top:.5em;
        padding:1em;
        transition: 0.2s ease-in-out;
    }
    .display:hover{
        margin-top: 0;
        font-size: 22px;
    }

</style>
