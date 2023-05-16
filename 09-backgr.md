###

    background-image: url('адрес картинки');
    background-repeat: repeat | repeat-x | repeat-y | no-repeat:
    background-position: x y;
    background-position: 50% 50%;
        /* Поставит фоновое изображение по центру */

    background-position: 100px 200px;
        /* Поставит фоновое изображение 100px от левого края и 200px от верха */

    background-size: auto | значение | cover | contain
    background-size: 200px; /* width=200px, а ширина пропорционально! */
    background-size: cover; /* растянет (покроет ковром) и обрежет  */
    background-size: contain; /* вместит полностью  */

## background-position

    background-position: x y

## для контентных картинок аналог

    object-fit и object-position

    для этого картинку -> в .thumb;
    -> img {
        display: block;
        width: 100%;
        height: 100%;
        }
    .thumbs {
        width: 200px;
        height: 300px;
        }

    .thumbs-album > img {
        object-fit: contain;
        object-position: 20px 20px;
        }
