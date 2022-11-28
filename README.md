# personal PortFolio

## Visão Geral

### Site de um portfólio pessoal (Tech) responsivo.
#

![](./Assets/images/personal-portifolio.png)

#
## Construido com:
- HTML
- CSS 
- SASS

## Bibliotecas utilizadas:
- [Font Awesome cdn link](https://cdnjs.com/libraries/font-awesome)

## Funcionalidades
- Site de portfólio pessoal (Tech) responsivo.
- Design totalmente responsivo.
#
## O que eu aprendi:

- Estilização com o SASS

```css
.destination .box-container {
   @include grid(27rem);

   .box {
      border-radius: 1rem;
      overflow: hidden;
      background: $bg-color;

      &:hover img {
         transform: scale(1.1);
      }

      .image {
         height: 20rem;
         overflow: hidden;
         width: 100%;

         img {
            height: 100%;
            width: 100%;
            object-fit: cover;
         }
      }

      .content {
         padding: 2rem;
         text-align: center;

         h3 {
            font-size: 2rem;
            color: $white;
         }

         p {
            padding: 1rem 0;
            font-size: 1.4rem;
            color: $light-color;
            line-height: 2;
         }

         a {
            font-size: 1.7rem;
            color: $blue;

            &:hover i {
               padding-left: 1rem;
            }

            i {
               padding-right: 0.7rem;
            }
         }
      }
   }
}
```
