<script>
export default {
    name: 'Contact',
}

</script>

<template>
    <div>
        <div class="flex w-full items-center py-5">
            <span class="w-1/2">
                <h1 class="text-3xl">Joshua Croucher</h1>
                <ul>
                    <li><a onclick="map.show()">15 Tilley Court Caboolture 4510</a></li>
                    <li><a href="tel:0431851558">0431 851 558</a></li>
                    <li><a href="mailto:Joshuacroucher1@gmail.com">Joshuacroucher1@gmail.com</a></li>
                </ul>
            </span>
            <span class="w-1/2">
                <img class="w-52 h-52 float-right" src="../../assets/Headshot.png" alt="Headshot">
            </span>
        </div>
        <dialog id="map">
            <button class="delete is-large float-right block" onclick="map.close()"></button>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3552.961356554347!2d152.96700277521037!3d-27.062967699498195!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6b93f25513efebf3%3A0x7a7840bde7ce4ef9!2s15%20Tilley%20Ct%2C%20Caboolture%20QLD%204510!5e0!3m2!1sen!2sau!4v1685499847855!5m2!1sen!2sau" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        </dialog>
    </div>
</template>

<style scoped>
</style>