<template>
  <div>
    <h2>Videók összevetése természetesség szempontjából</h2>
    <div>
        <video width="320" height="240" controls>
            <source src="http://web.unideb.hu/nagyzk/2018-06-15_DE_AOK_diplomaoszt%c3%b3_video.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        <video width="320" height="240" controls>
            <source src="http://web.unideb.hu/nagyzk/2018-06-23_DE_GYTK_diplomaoszt%c3%b3_video.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
    <div>
        Mennyire tartja természetesnek a bal oldali videót?
        <ul>
            <li><input type="radio" name="naturality-left" value="1" checked>Egyáltalán nem természetes</input></li>
            <li><input type="radio" name="naturality-left" value="2">Kicsit természetes</input></li>
            <li><input type="radio" name="naturality-left" value="3">Félig-meddig természetes</input></li>
            <li><input type="radio" name="naturality-left" value="4">Majdnem természetes</input></li>
            <li><input type="radio" name="naturality-left" value="5">Nagyon természetes</input></li>
        </ul>
        Mennyire tartja természetesnek a jobb oldali videót?
        <ul>
            <li><input type="radio" name="naturality-right" value="1" checked>Egyáltalán nem természetes</input></li>
            <li><input type="radio" name="naturality-right" value="2">Kicsit természetes</input></li>
            <li><input type="radio" name="naturality-right" value="3">Félig-meddig természetes</input></li>
            <li><input type="radio" name="naturality-right" value="4">Majdnem természetes</input></li>
            <li><input type="radio" name="naturality-right" value="5">Nagyon természetes</input></li>
        </ul>
        <button>Következő</button>
    </div>
  </div>
</template>

<script>
export default {
    name: 'about'
}
</script>

<style>
</style>

