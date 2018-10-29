<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-md-8 pr-0">
                <form>
                <fieldset>
                    <legend class="text-uppercase" style="font-size: 40px;letter-spacing: 0 !important;">&nbsp;NÄSTA LÄSTIPS&nbsp;</legend>
                    <FooterPostBoxes/>
                    <FooterPostBoxes/>
                </fieldset>
                </form>   
            </div>
            <div class="col-md-4 pt-2">
                <JumbotronPost/>
            </div>
        </div> 
    </div>
</template>

<script>
import FooterPostBoxes from './FooterPostBoxes'
import JumbotronPost from './JumbotronPost'
export default {
    name: 'FooterPost',
    components: {
        FooterPostBoxes,
        JumbotronPost
    }
}
</script>

<style>
fieldset{
    border: 1px dashed #343a40 !important;
    /* margin-left: 20px !important; */
}
legend{
    text-align: center;
    width: unset !important;
    font-family: 'Abril Fatface', cursive;
}
</style>

