<template>
    <div>
        <p>Lamba Durumu :  {{ status }} </p>
        <hr>
        <button @click="openLamb">Lambayı Aç/Kapat</button>
    </div>
</template>
<script>
export default {
    data : function(){
        return {
            status : "Kapalı"
        }
    },
    methods : {
        openLamb(){
            this.status = "Açık....."
        }
    }
}
</script>