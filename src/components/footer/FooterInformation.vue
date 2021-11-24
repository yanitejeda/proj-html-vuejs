<template>
    <div class="card card-s my-3 py-3 bg-card-footer col-3">     
        <div class="card-body">
            <h4 class="font-W6">{{tittle}}</h4>
            <p class="card-text font-w3 color-grey">
                {{info1}}
            </p>
            <p class="card-text font-w3 color-grey">
                {{info2}}
            </p>
            <p class="card-text font-w3 color-grey">
                {{info3}}
            </p>
            <p class="card-text font-w3 color-grey">
                {{info4}}
            </p>
            <p class="card-text font-w3 color-grey">
                {{info5}}
            </p>
            <p class="card-text font-w3 color-grey">
                {{info6}}
            </p>
            
        </div>
    </div>
    
</template>
<script>
export default {
    name:"FooterInformation",
    props:['tittle','info1','info2','info3','info4','info5','info6']
}
</script>