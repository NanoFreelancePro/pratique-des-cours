/* EXERCICES */
/* BOUCLE */
/* 
Définir des VARIABLES
définir une MAP
Créer une MIXIN et y integrer la boucle
avec @each $key, $value in $map


@mixin mixin-name ($map-name){
    @each $key, $value in $map-name{
        &--#{$key}{
            background: $value;
        }
    }
}

Dans le code SASS : 
.btn{
    @include mixin-name($map-name);
}
*/

liens : https://openclassrooms.com/fr/courses/6106181-simplifiez-vous-le-css-avec-sass/6606591-utilisez-les-boucles-dans-sass-pour-fluidifier-votre-code