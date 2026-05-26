# Relevamiento profundo del Drive `7. Page Breakdowns and Wireframes`

Fecha de relevamiento: `2026-05-26`  
Drive analizado: `https://drive.google.com/drive/folders/12p9jdfB1MrOiV8sJG5UkxKWqJJ-QWonf?usp=sharing`

## Alcance y metodo

Este relevamiento se rehizo con procesamiento real de los archivos descargados desde el Drive. Para cada asset se usaron, segun el caso:

- `ffprobe` para metadata de video/audio.
- `ffmpeg` para extraer fotogramas y audio.
- `faster-whisper` para transcribir el audio de todos los videos.
- `pdfinfo` y `pdftotext` para extraer texto y metadatos de todos los PDFs.

Criterio estricto:

- Cuando un PDF no devolvio texto util, se deja explicitado y no se inventa contenido.
- Cuando un hallazgo sale del audio de un video, se apoya en la transcripcion real de ese archivo.
- Cuando un archivo es puramente visual, el texto describe solo lo efectivamente verificable por nombre, metadata, texto extraido o video homonimo de la misma familia.

## Totales del set

- `50` archivos en total, incluyendo `.DS_Store`.
- `16` videos con audio transcripto.
- `33` PDFs con texto extraido o validacion de ausencia de texto legible.
- El idioma dominante del audio transcripto es `ingles`.
- El tema dominante del set es `wireframes y page breakdowns para funnels, e-commerce, lead generation y landings de conversion`.

## .DS_Store

- Tipo MIME: `application/octet-stream`
- Lectura verificable: archivo tecnico de macOS/Finder, sin contenido funcional de negocio.

## Familia 1: Homepage

Bloque de archivos asociado a `Homepage`. Se listan primero los videos y luego los PDFs de la misma familia.

### 1. Homepage.mp4

- Tipo MIME: `video/mp4`
- Tamano declarado en Drive: `51.1 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1pyAeJhQEVOFN7N9ntOWHGfcvJ9U1YTBT`
- Duracion real detectada: `308.4 s`
- Idioma detectado en la transcripcion: `en` (0.89)
- Segmentos transcritos: `69`
- Fotogramas de control generados: `start`, `mid`, `end`

#### Hallazgos verificables del audio

- Okay, so homepage layouts and this is an e-con store homepage layout and you just notice as we go through this page All we're doing is layering everything that we've learnt within the modules, especially when it comes to the design module On top of each other 
- You just the ultimate goal is it for it to be red pretty early on On your navigation you have your links you have your logo whether that's left the line or central line it doesn't really matter and then you keep your kind of user kind of Options like your cart
- A lot of people will use sliders on their home pages.
- I personally don't like them I know they serve a purpose some of times, but I would tend to stick to static above the fold You then have your three Benefit driven bullet points that tell us the benefit of a of your store So speak to us about the the benefits w

#### Extracto de transcripcion

```text
Okay, so homepage layouts and this is an e-con store homepage layout and you just notice as we go through this page
All we're doing is layering everything that we've learnt within the modules, especially when it comes to the design module
On top of each other when we talk about that page layout when we talked about above the fold elements to include
I'm just gonna kind of briefly go over them
So never underestimate the power of a notice bar notice bar should be useful things like free shipping
Reminders when it comes to thresholds, but also seasonal sales and he sells who might have on promotions
Etc
Make sure that no-tours bar stands out
When it comes to color make sure it clashes and it's red, okay?
You just the ultimate goal is it for it to be red pretty early on
On your navigation you have your links you have your logo whether that's left the line or central line
it doesn't really matter and then you keep your kind of user
kind of
Options like your cart your profile your search etc
Set for it to your other links just to just a clean it up when it comes to actual navigation all links on your
Stores themselves or on your pages trying to keep them between sort of five and six the more you offer the less people will click
I would look at your heat map software
Which we cover in the ongoing CRM module and see what everyone's clicking and just kill any of the links that are not clicking, okay
When it comes to above the fold we're just ticking those boxes
So we have our trust and credibility bar along the top, you know making sure that we
Stipulate things that make us trusted as a company
Not gonna go into too much detail on each every element because we do that inside the design module
You then have your social proof you have a clear value proposition featuring a benefit
```

## Familia 2: Product page

Bloque de archivos asociado a `Product page`. Se listan primero los videos y luego los PDFs de la misma familia.

### 2. Product page.mp4

- Tipo MIME: `video/mp4`
- Tamano declarado en Drive: `100 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1kGcHEYsG0xJF2FEqTu4QFxRMuWnAUSQ6`
- Duracion real detectada: `634.8 s`
- Idioma detectado en la transcripcion: `en` (0.93)
- Segmentos transcritos: `106`
- Fotogramas de control generados: `start`, `mid`, `end`

#### Hallazgos verificables del audio

- Okay, so the product page wireframe and I want to start by saying that every section I'm about to show you as far as the kind of ideal framework and wireframe for a product product page should be dynamic based on your store.
- So if you have a store with multiple skews, let's say thousands of skews, I do not expect each and every one of these sections to be unique per product page.
- What you need to do is make a decision on what parts can be unique and what can be broad across your store but try and get as many of these sections following this framework in as possible across all of your products.
- Again, I'll show you how these can kind of be dynamic.
- So most importantly, of course above the fold, really importantly on mobile, go and have a look at the mobile wireframe and make sure that all the essential elements of above the fold, but I'll walk you through here.

#### Extracto de transcripcion

```text
Okay, so the product page wireframe and I want to start by saying that every section
I'm about to show you as far as the kind of ideal framework and wireframe for a product
product page should be dynamic based on your store. So if you have a store with multiple
skews, let's say thousands of skews, I do not expect each and every one of these sections to
be unique per product page. What you need to do is make a decision on what parts can be unique
and what can be broad across your store but try and get as many of these sections following this
framework in as possible across all of your products. Again, I'll show you how these can kind of be
dynamic. So most importantly, of course above the fold, really importantly on mobile, go and have a
look at the mobile wireframe and make sure that all the essential elements of above the fold,
but I'll walk you through here. When it comes to your, when it comes to your links, as I said, in the home
page, try and make sure that these kind of minimal links. So five to six links at the most
any over that is overkill. Use your notice bars, of course, dynamic kind of seasonal sales or shipping
free shipping prompts, trust policy bar underneath really important, making sure that you are a
trusted company, visually showing that. But let's have a look at the individual elements. Now,
I highly recommend you go and watch the designing design modules and go through each and every lesson
inside that design module because I'll break down these elements even further and that's crucial.
But let's start on the left hand side. Have a clear visual of an image, make sure you use multiple
cases of really important and use multiple images here, making sure that you have
Chevron's on mobile to showcase people that can go through the images. It's just a bet
```

### 2.1 Product page - desktop.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `19.9 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1JZ1H8Yhf2loYmhzeY2Kt5TEkuc5D89fZ`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `7`
- Caracteres extraidos: `79`

#### Texto verificable extraido del PDF

```text
Compar
     ison
            Br
             and
            Logo   C1   C2
```

#### Lectura verificable del archivo

- El PDF devuelve muy poco texto, lo que confirma que se trata principalmente de un wireframe visual. Las pocas etiquetas extraidas sirven para ubicar modulos o labels, no para leer copy de negocio completo.
- El archivo comparte familia con `2. Product page.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

### 2.2 Product page - mobile.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `3.7 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `16LZsTtbvj9XOUTG4x1xOTc7LuU7lIy7A`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `6`
- Caracteres extraidos: `47`

#### Texto verificable extraido del PDF

```text
Compar
     ison
   Br
    and
   Logo   C1
```

#### Lectura verificable del archivo

- El PDF devuelve muy poco texto, lo que confirma que se trata principalmente de un wireframe visual. Las pocas etiquetas extraidas sirven para ubicar modulos o labels, no para leer copy de negocio completo.
- El archivo comparte familia con `2. Product page.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

## Familia 3: Collections page

Bloque de archivos asociado a `Collections page`. Se listan primero los videos y luego los PDFs de la misma familia.

### 3. Collections page.mp4

- Tipo MIME: `video/mp4`
- Tamano declarado en Drive: `43.9 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `11EB1HKuPei_UNegZrGlUOwL279Q-2egs`
- Duracion real detectada: `266.9 s`
- Idioma detectado en la transcripcion: `en` (0.90)
- Segmentos transcritos: `103`
- Fotogramas de control generados: `start`, `mid`, `end`

#### Hallazgos verificables del audio

- Okay, so let's talk about collection pages.
- Collection pages are so important for your stores, or for your websites, and it's a right and wrong way to do them.
- What's the most important thing about a collection page?
- Well, it's actually just showing off the collection.
- Okay, having as many products within that fold, above the fold as possible.

#### Extracto de transcripcion

```text
Okay, so let's talk about collection pages.
Collection pages are so important for your stores,
or for your websites,
and it's a right and wrong way to do them.
So I'm gonna walk through it.
What's the most important thing about a collection page?
Well, it's actually just showing off the collection.
Okay, having as many products within that fold,
above the fold as possible.
When it comes to mobile,
use a two by two ratio.
What I mean is do not have one product,
then another product, then another product,
have two small products, two small products,
and make sure you show it at least two.
If not four above the fold on load.
Okay, going back to desktop,
we've used this kind of gray box in the background
to symbolize an image.
I know a lot of people love using these big bananas
at the top of their fold on collection pages.
Try and keep it as thin as possible.
I'm not saying don't use images,
because I know it visually is attractive to consumers.
However, try and keep them as thin as possible.
I would AB test having an image,
getting rid of the image, and just pulling everything up.
What's more important, okay?
This can be used very, very well,
so a little small box over the image,
making sure that you have a solid background,
so it's easily read on desktop and mobile,
have an emotive headline.
So have a headline, explain the benefit of the collection.
Have a social proof, so a lot of people don't do this.
Sorry, but have social proof.
So 4.5, have a happy customer's, for example.
And a little description above the collection itself.
However, as I said, I would split tests or AB test,
having this big hero section versus getting rid of it
and just having this all on one thin line,
but most importantly, on mobile,
do not show that big banner, okay?
It's just gonna push your pr
```

### 3.1 Collection page - desktop.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `72.7 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1UhinA8pj0vYg1BMAioUN5iJiX8K-2t-3`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `72`
- Caracteres extraidos: `573`

#### Texto verificable extraido del PDF

```text
ADD TO CART>   ADD TO CART>   ADD TO CART>
VI
 EW PRODUCT    VI
                EW PRODUCT    VI
                               EW PRODUCT
ADD TO CART>   ADD TO CART>   ADD TO CART>
VI
 EW PRODUCT    VI
                EW PRODUCT    VI
                               EW PRODUCT
ADD TO CART>   ADD TO CART>   ADD TO CART>
VI
 EW PRODUCT    VI
                EW PRODUCT    VI
                               EW PRODUCT
ADD TO CART>   ADD TO CART>   ADD TO CART>
VI
 EW PRODUCT    VI
                EW PRODUCT    VI
                               EW PRODUCT
```

#### Lectura verificable del archivo

- El PDF si aporta texto util: botones, labels, encabezados o microcopy de la maqueta. Eso permite verificar estados, CTA, labels de formulario o estructura de catalogo segun la familia.
- El archivo comparte familia con `3. Collections page.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

### 3.2 Collection page - mobile.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `24.3 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `140Q-x4q2EZqdVbNh5XO1DHMpM1XTLyqR`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `96`
- Caracteres extraidos: `645`

#### Texto verificable extraido del PDF

```text
ADD TO CART>   ADD TO CART>
VI
 EW PRODUCT    VI
                EW PRODUCT
ADD TO CART>   ADD TO CART>
VI
 EW PRODUCT    VI
                EW PRODUCT
ADD TO CART>   ADD TO CART>
VI
 EW PRODUCT    VI
                EW PRODUCT
ADD TO CART>   ADD TO CART>
VI
 EW PRODUCT    VI
                EW PRODUCT
ADD TO CART>   ADD TO CART>
VI
 EW PRODUCT    VI
                EW PRODUCT
ADD TO CART>   ADD TO CART>
VI
 EW PRODUCT    VI
                EW PRODUCT
ADD TO CART>   ADD TO CART>
VI
 EW PRODUCT    VI
                EW PRODUCT
ADD TO CART>   ADD TO CART>
VI
 EW PRODUCT    VI
                EW PRODUCT
```

#### Lectura verificable del archivo

- El PDF si aporta texto util: botones, labels, encabezados o microcopy de la maqueta. Eso permite verificar estados, CTA, labels de formulario o estructura de catalogo segun la familia.
- El archivo comparte familia con `3. Collections page.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

## Familia 4: Cart draw

Bloque de archivos asociado a `Cart draw`. Se listan primero los videos y luego los PDFs de la misma familia.

### 4. Cart draw.mp4

- Tipo MIME: `video/mp4`
- Tamano declarado en Drive: `38.2 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1IaDHK0hX6NJMmSxo0JSrMwHYBwCJnjJ5`
- Duracion real detectada: `241.5 s`
- Idioma detectado en la transcripcion: `en` (0.90)
- Segmentos transcritos: `90`
- Fotogramas de control generados: `start`, `mid`, `end`

#### Hallazgos verificables del audio

- Okay, so this is our cart drawer or cart slider.
- Whatever you want to call it, this is typically used obviously for e-com, but you can use this on any, anywhere where you sell a product ready, whether that's a course, a physical product.
- It doesn't matter, cart, sliders and cart drawers, give a real good user experience and you can optimize them to increase things like your average order volume and I'll show you how.
- So if you imagine, as you add a product cart, this slides out, one thing I would do that we haven't shown here, but I would lower the opacity, make sure the opacity of the kind of rest of the site, lower so you've got this kind of grayish color, so it just dra
- Have it pop out as soon as a product is added to cart, but most importantly, a lot of you will not do this, but when you actually click the cart slider, so you'll all have like a little shopping cart, icon at the top of your product pages, for example, and whe

#### Extracto de transcripcion

```text
Okay, so this is our cart drawer or cart slider.
Whatever you want to call it, this is typically used
obviously for e-com, but you can use this on any,
anywhere where you sell a product ready,
whether that's a course, a physical product.
It doesn't matter, cart, sliders and cart drawers,
give a real good user experience
and you can optimize them to increase things like your average
order volume and I'll show you how.
So this is our slider.
So if you imagine, as you add a product cart,
this slides out, one thing I would do that we haven't shown here,
but I would lower the opacity,
make sure the opacity of the kind of rest of the site,
lower so you've got this kind of grayish color,
so it just draws attention and focus to the cart slider.
Have it pop out as soon as a product is added to cart,
but most importantly, a lot of you will not do this,
but when you actually click the cart slider,
so you'll all have like a little shopping cart,
icon at the top of your product pages, for example,
and when you click it and it's empty,
you need to use that empty space.
Don't just have a cart that comes out and has nothing in it.
This is a real good opportunity to sell you to your customers.
So first and foremost, I'm showing you the empty cart slider.
So you should say that the cart is empty,
but here you should have one of several things.
If you have a multi-scued store,
and you have lots of products,
suggest the best collections here,
at the top have best sellers as a link.
So these are to symbolize buttons with text on.
So you have best collection, you might best sellers,
you might then have your top collections down,
and just suggest products for your customers.
So this can just take them back to the collection page.
Now when you add a cart, a product to cart,
and you actually ha
```

### 4.1 Cart Draw Empty - desktop.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `1.6 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1d4jaTUEj9j--iaHCu8afEKNBbKB0aCAV`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `184`
- Caracteres extraidos: `6529`

#### Texto verificable extraido del PDF

```text
Add promotional shipping notification goes here
                                                         Websitename                                                                                                          Your  cart (0 i t ems)
Lorem.     ipsum   dolor   sit   amet,                                                                                                                                         $USD         account_circle
    hhjjhggjkj                           hhjjhggjkj                                                                   hhjjhggjkj                                                  Your   cart is empty
                                                                                                                                                                                   hhjjhggjkj
                                                                                                                                                                                What are you looking for?
Lorem ipsum
                                                                            Val    u   e  Proposit io n Featuri n g Benefit
```

#### Lectura verificable del archivo

- El PDF si aporta texto util: botones, labels, encabezados o microcopy de la maqueta. Eso permite verificar estados, CTA, labels de formulario o estructura de catalogo segun la familia.
- El archivo comparte familia con `4. Cart draw.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

### 4.2 Cart Draw Empty - mobile.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `1.4 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1-9uxSw82DIYlOctIhinD3QrfFP3jBTDH`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `75`
- Caracteres extraidos: `1453`

#### Texto verificable extraido del PDF

```text
Add         promotional              shipping     notification
                 Your cart (0 items)
                          Websitename
                       Your cart  is empty
                            hhjjhggjkj
                What                       are     you      looking       for?
                                             select    an    option
                                             select    an    option
                                             select    an    option
                                             select    an    option
                                           4.8/5   Add      promotional   shippi
Value     Proposition
  Free standard shipping on orders £100+
Featuring Benefit
Starting from $XX                                             Running low on stock
               Lorem                       ipsum      dolor      sit      amet,
check_circle
               Lorem                       ipsdfdfdfdfdfdfdfdfum
check_circle
               Lorem                       ipsum      detur      adipiscin
check_circle
                                   Secure Checkout
                     keyboard_arrow_down
                          hhjjhgg
```

#### Lectura verificable del archivo

- El PDF si aporta texto util: botones, labels, encabezados o microcopy de la maqueta. Eso permite verificar estados, CTA, labels de formulario o estructura de catalogo segun la familia.
- El archivo comparte familia con `4. Cart draw.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

### 4.3 Cart Draw Full - desktop.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `1.7 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1jhvKpbCCMqMHGOoIgjTyXZlJaaX0texu`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `218`
- Caracteres extraidos: `8507`

#### Texto verificable extraido del PDF

```text
Add promotional shipping notification goes here
                                                         Websitename                                                                                                                     Your  cart (1 i t ems)
Lorem.     ipsum   dolor   sit   amet,                                                                                                                                                    $USD    account_circle
                                                                                                                                                                                   What are you looking for? are
                                                                                                                                                                                   you looking for?
    hhjjhggjkj                           hhjjhggjkj                                                                           hhjjhggjkj                                                   hhjjhggjkj
```

#### Lectura verificable del archivo

- El PDF si aporta texto util: botones, labels, encabezados o microcopy de la maqueta. Eso permite verificar estados, CTA, labels de formulario o estructura de catalogo segun la familia.
- El archivo comparte familia con `4. Cart draw.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

### 4.4 Cart Draw Full - mobile.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `1.5 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1-cHX2-qCkWcetrJoy44JVaIGIbC6NhxE`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `105`
- Caracteres extraidos: `2463`

#### Texto verificable extraido del PDF

```text
Add         promotional                   shipping        notification
                      Your cart (1 items)
                            Websitename
               What         are               you          looking            for?
               you      looking                      for?
                                                  hhjjhggjkj
                                                  select           an     option
                                                  select    an
                                                  select    an
                                                                            £50.00 £45.00
                                                     -        1      +
               You May Also Like
                                                  select           an     option
                                                  select    an
                                                  select    an
                                                                            £50.00 £45.00
                                                                   Add To Cart
                                             4.8/5       Add       p
```

#### Lectura verificable del archivo

- El PDF si aporta texto util: botones, labels, encabezados o microcopy de la maqueta. Eso permite verificar estados, CTA, labels de formulario o estructura de catalogo segun la familia.
- El archivo comparte familia con `4. Cart draw.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

## Familia 5: Sales page

Bloque de archivos asociado a `Sales page`. Se listan primero los videos y luego los PDFs de la misma familia.

### 5. Sales page.mp4

- Tipo MIME: `video/mp4`
- Tamano declarado en Drive: `36.7 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1j0C4Bc-1ZnlqzoP441IMcPIrr0Lb17M-`
- Duracion real detectada: `225.6 s`
- Idioma detectado en la transcripcion: `en` (0.82)
- Segmentos transcritos: `46`
- Fotogramas de control generados: `start`, `mid`, `end`

#### Hallazgos verificables del audio

- Okay, so I will cover the elements and the layout of the sales page wife name very quickly But most importantly is to establish why you would use a sales page as opposed to a product page And really the only difference is that a sales page is more aggressive I
- It's a dedicated sales page with zero traffic needs So you can't click anywhere else It has our trust policy bar of course It does it has those crucial elements above the fold including social proof including value proposition Three benefit driven bullet point
- You don't have to follow the kind of typical product page left and right Framework above the fold you could have a nice image the most important thing is those Principles on the right hand side of the screen when I'm looking at it are above the fold So you cou
- Then we have our social proof to desire section testimonials and reviews Make sure that you can if you if you can utilize those kind of UGC style videos Gifts people taking real raw pictures real videos on their cameras They work very very well especially if y
- We have one clear call to action and notice We don't have any footer.

#### Extracto de transcripcion

```text
Okay, so I will cover the elements and the layout of the sales page wife name very quickly
But most importantly is to establish why you would use a sales page as opposed to a product page
And really the only difference is that a sales page is more aggressive
It's more direct response and this is what I would use if I was driving a lot of paid media to a specific page selling a product
Now I would definitely split test 50% of traffic versus the product page itself
However, what we found is when you have a more direct response dedicated sales page
It typically converts a little bit better the reason is you don't have any traffic distractions
If you notice in the navigation, there's no links
There's no other pages you can click to it's purely just the logo and then it follows all of our principles
So it just keeps people dedicated on this page. It's a dedicated sales page with zero traffic needs
So you can't click anywhere else
It has our trust policy bar of course
It does it has those crucial elements above the fold including social proof including value proposition
Three benefit driven bullet points keeping the call to action very simple
On a sales page normally you would just have one call to action, which is like get my now rush my order whatever that may be
Payment sales trust and credibility obviously those shipping details and a review
Also not forgetting our product images now again
You can get creative with this on dedicated sales pages. You don't have to follow the kind of typical product page left and right
Framework above the fold you could have a nice image the most important thing is those
Principles on the right hand side of the screen when I'm looking at it are above the fold
So you could play around with this image it could just be a one image as well
We t
```

### 5.1 Sales - desktop.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `18.5 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1YLEWcDPDbcgOJYd53gsNi82Yq150KqMs`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `7`
- Caracteres extraidos: `79`

#### Texto verificable extraido del PDF

```text
Compar
     ison
            Br
             and
            Logo   C1   C2
```

#### Lectura verificable del archivo

- El PDF devuelve muy poco texto, lo que confirma que se trata principalmente de un wireframe visual. Las pocas etiquetas extraidas sirven para ubicar modulos o labels, no para leer copy de negocio completo.
- El archivo comparte familia con `5. Sales page.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

### 5.2 Sales - mobile.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `3.5 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1VC2JoLpDGIlmmqz3eawuDk5lXF-YdWn4`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `6`
- Caracteres extraidos: `47`

#### Texto verificable extraido del PDF

```text
Compar
     ison
   Br
    and
   Logo   C1
```

#### Lectura verificable del archivo

- El PDF devuelve muy poco texto, lo que confirma que se trata principalmente de un wireframe visual. Las pocas etiquetas extraidas sirven para ubicar modulos o labels, no para leer copy de negocio completo.
- El archivo comparte familia con `5. Sales page.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

## Familia 6: Listicle page

Bloque de archivos asociado a `Listicle page`. Se listan primero los videos y luego los PDFs de la misma familia.

### 6. Listicle page.mp4

- Tipo MIME: `video/mp4`
- Tamano declarado en Drive: `48.6 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1pxkuMoHHe_KmfMHmJeUa1D20g1OUh87a`
- Duracion real detectada: `303.6 s`
- Idioma detectado en la transcripcion: `en` (0.90)
- Segmentos transcritos: `106`
- Fotogramas de control generados: `start`, `mid`, `end`

#### Hallazgos verificables del audio

- Okay, the listicle, another form of pre-cell, so effectively, again, what this page is doing is it's pre-selling someone, it's warming someone up before they actually then go and take action and purchase your product.
- So it's a really good native way for you to advertise your product before they actually click on a page that says, take action and buy me, okay?
- Again, typically this is done to pre-educate someone on the product that may need a little bit more information.
- It kind of serves as a middle step ad-plaked, going to the listicle, then to your product page or sales page or sometimes straight through to your car or checkout.
- Now, a listicle is exactly what it says on the tin.

#### Extracto de transcripcion

```text
Okay, the listicle, another form of pre-cell,
so effectively, again, what this page is doing
is it's pre-selling someone,
it's warming someone up before they actually then
go and take action and purchase your product.
So it's a really good native way for you to
advertise your product before they actually click on a page
that says, take action and buy me, okay?
Again, typically this is done to pre-educate someone
on the product that may need a little bit more information.
It kind of serves as a middle step ad-plaked,
going to the listicle, then to your product page or sales page
or sometimes straight through to your car or checkout.
Now, a listicle is exactly what it says on the tin.
It's a list, okay?
It's typically a list of say five benefits, 10 key points.
I would keep the list as kind of concise as possible.
I wouldn't do 10, 15, 20 things on that list.
Five or six is about right, but let's walk through
how you laid this out.
So again, you'll notice no distractions above the phone,
no navigational links, nothing.
Yes, you can include a call to action
that just goes through to your product page.
However, sometimes I would be test having this just down
the bottom of the fold, similar to an avatar or we don't want
too many call to actions until we've actually pre-sold them.
So we need to do that.
Most importantly, above the fold is this.
It's making it look as authentic and organic as possible.
So having a clear headline that's value driven,
obviously mentioning what they get from the article,
for example, five benefits to taking a multivitamin every day.
But this is super important.
A picture of the person, the author's first and last name
and a dynamic date.
So it makes it look really, really real
and trustworthy because we've got a picture of the author,
first and l
```

### 6.1 Listicle - desktop.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `4.1 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1HXDpwiFUpYpU0OKceeUcD0rZgx1wp88C`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `22`
- Caracteres extraidos: `415`

#### Texto verificable extraido del PDF

```text
Headl
    ine
SubHeadl
       ine
    Mar
      ch1
        1,
         2023
                1Headl
                     ine
                2Headl
                     ine
                3Headl
                     ine
                4Headl
                     ine
                5Headl
                     ine
                6Headl
                     ine
      Of
       fer
```

#### Lectura verificable del archivo

- El PDF devuelve muy poco texto, lo que confirma que se trata principalmente de un wireframe visual. Las pocas etiquetas extraidas sirven para ubicar modulos o labels, no para leer copy de negocio completo.
- El archivo comparte familia con `6. Listicle page.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

### 6.2 Listicle - mobile.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `5 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1nOSwVqVqHZYUZOL_MhX9MZTnRgsssySY`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `22`
- Caracteres extraidos: `213`

#### Texto verificable extraido del PDF

```text
Headl
    ine
SubHeadl
       ine
   Mar
     ch1
       1,
        2023
1Headl
     ine
2Headl
     ine
3Headl
     ine
4Headl
     ine
5Headl
     ine
6Headl
     ine
  Of
   fer
```

#### Lectura verificable del archivo

- El PDF devuelve muy poco texto, lo que confirma que se trata principalmente de un wireframe visual. Las pocas etiquetas extraidas sirven para ubicar modulos o labels, no para leer copy de negocio completo.
- El archivo comparte familia con `6. Listicle page.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

## Familia 7: Advertorial page

Bloque de archivos asociado a `Advertorial page`. Se listan primero los videos y luego los PDFs de la misma familia.

### 7. Advertorial page.mp4

- Tipo MIME: `video/mp4`
- Tamano declarado en Drive: `61.1 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1wJHN4ITTh1UsftyNqaaWCmZyeNzXQjnO`
- Duracion real detectada: `376.4 s`
- Idioma detectado en la transcripcion: `en` (0.87)
- Segmentos transcritos: `68`
- Fotogramas de control generados: `start`, `mid`, `end`

#### Hallazgos verificables del audio

- Okay, so let's have a look at our advertorial wireframe and traditionally advertorials sit as a pre-cell.
- They help you pre-cell your offer, your product, your course, whatever it may be that comes after this initial page.
- So they sit in between the ad and the sales page.
- So you drive media from the ad or from an email or wherever it may be to the advertorial and it gives you a chance to pre-cell and somewhat educate your code consumers on your product before you send them to a sales page or a sign-up page or a lead-gem page.
- Typically these are used for products that need a little bit more education around them.

#### Extracto de transcripcion

```text
Okay, so let's have a look at our advertorial wireframe and traditionally
advertorials sit as a pre-cell. They help you pre-cell your offer, your product, your course,
whatever it may be that comes after this initial page. So they sit in between the ad and the sales page.
So you drive media from the ad or from an email or wherever it may be to the advertorial
and it gives you a chance to pre-cell and somewhat educate your code consumers on your product
before you send them to a sales page or a sign-up page or a lead-gem page. Typically these are used
for products that need a little bit more education around them. So they need, you know,
long-form copy that helps inform a consumer exactly of the product and the benefits of the product.
Traditionally, and typically these are written by third party. So let's say for example,
you're selling the conversion-vitt multi-vittamin-pill. This wouldn't sit on conversion-vitt-multi-vittamin.com.
This would sit on multi-vittaminreviews.com, you know, a middle party that would then
pre-cell in a native organic way that the click through to the product. So a few things to note,
you need to make these look as native as possible. So they're almost blog formats.
So you have your website logo or name up here. These could be links but what I would do is a
little bit of a trick. If people click the link either scroll to a section within the page
or click through to the offer, just keep it as direct response as possible. This symbolizes this
sort of big grey box here. symbolizes maybe an image or a header of a of the article to help
visually entice the consumer into it. You have your title here, which would be something that's kind of
a little bit click-bathy, a little bit like, you know, John found he could live a healthy and happy
life with
```

### 7.1 Advertorial - desktop.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `368 KB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1aYE-sZnNNn3rOD7IH897lzvUBNgRmmUV`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `0`
- Caracteres extraidos: `1`

#### Texto verificable extraido del PDF

No se extrajo texto legible por `pdftotext`. Esto indica que el archivo es mayormente visual o que el texto no esta disponible como capa seleccionable.

#### Lectura verificable del archivo

- Este PDF no aporto texto seleccionable. La señal verificable queda limitada a su existencia dentro de la familia `Advertorial page` y al video homonimo que explica esa misma estructura.
- El archivo comparte familia con `7. Advertorial page.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

### 7.2 Advertorial - mobile.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `186 KB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1a0gvrFQtwoh8yiIUaWL4njpmhwdLljRG`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `0`
- Caracteres extraidos: `1`

#### Texto verificable extraido del PDF

No se extrajo texto legible por `pdftotext`. Esto indica que el archivo es mayormente visual o que el texto no esta disponible como capa seleccionable.

#### Lectura verificable del archivo

- Este PDF no aporto texto seleccionable. La señal verificable queda limitada a su existencia dentro de la familia `Advertorial page` y al video homonimo que explica esa misma estructura.
- El archivo comparte familia con `7. Advertorial page.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

## Familia 8: Quiz page

Bloque de archivos asociado a `Quiz page`. Se listan primero los videos y luego los PDFs de la misma familia.

### 8. Quiz page.mp4

- Tipo MIME: `video/mp4`
- Tamano declarado en Drive: `41 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1gAa2PNB1n7gdgjpjPcB3Bl_mmI7rMtzs`
- Duracion real detectada: `285.7 s`
- Idioma detectado en la transcripcion: `en` (0.84)
- Segmentos transcritos: `34`
- Fotogramas de control generados: `start`, `mid`, `end`

#### Hallazgos verificables del audio

- Okay, so let's talk about quiz pages, quiz funnels, survey funnels, whatever you want to call them, what these are essentially are, when you take someone down a specific journey to place them with a if-conditional outcome.
- So, everyone who takes the survey will not get the same results as the outcome.
- Now, you would use these kind of quiz survey funnels for a product that typically doesn't have a one-size-fits-all.
- So, let's say it's a skin care product where dry skin versus flaky skin versus soft skin versus rough skin, or could you benefit from a different type of product, you would use a quiz and survey funnel to pre-qualify or pre-quies your consumers, to then give t
- So, the person with flaky skin would then at the bottom end of the funnel get suggested a flaky skin moisturizer versus the person with dry skin, when they get their results would get paired with a dry skin product.

#### Extracto de transcripcion

```text
Okay, so let's talk about quiz pages, quiz funnels, survey funnels, whatever you want to call them,
what these are essentially are, when you take someone down a specific journey to place them with a
if-conditional outcome. So, everyone who takes the survey will not get the same results as the outcome.
Now, you would use these kind of quiz survey funnels for a product that typically doesn't have a one-size-fits-all.
So, let's say it's a skin care product where dry skin versus flaky skin versus soft skin versus rough skin,
or could you benefit from a different type of product, you would use a quiz and survey funnel to pre-qualify or pre-quies your consumers,
to then give them a more tailored and better experience with a product specific outcome.
So, the person with flaky skin would then at the bottom end of the funnel get suggested a flaky skin moisturizer versus the person with dry skin,
when they get their results would get paired with a dry skin product. So, it's more of a better customer experience,
it allows you to give that almost in person feel when it comes to kind of a concierge to suggest the best products.
Okay, so let's talk about how you lay them out. You will notice that all of this page is above the fold. I can't scroll,
I'm not going anywhere else, I'm keeping everyone direct within that above the fold screen. You have your little logo here,
but we get rid of all the navelings. So, we don't have any navelings on this page, the reason being, they're just traffic distractions,
they're just links that we click and then we'd be away from the survey page. So, get rid, make it headless and footless, get rid of your head and footer when it comes to these pages.
Even if you're clicking to this page from your store or your site, get rid of these pages.
I have a val
```

### 8.1 Quiz - desktop.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `1.1 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1dLOJN5nQNU15RlBr5G3grfgUJTFCgQYq`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `15`
- Caracteres extraidos: `239`

#### Texto verificable extraido del PDF

```text
Val
  uePr
     oposi
         ti
          onHeadl
                ine
       Quest
           ion?
   Thi
     sshoul
          dtakel
               esst
                  han3mi
                       nut
                         es
```

#### Lectura verificable del archivo

- El PDF devuelve muy poco texto, lo que confirma que se trata principalmente de un wireframe visual. Las pocas etiquetas extraidas sirven para ubicar modulos o labels, no para leer copy de negocio completo.
- El archivo comparte familia con `8. Quiz page.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

### 8.2 Quiz - mobile.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `1.3 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1pR3LTupyM-uySQ_KDxyBMge4vHlodhEC`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `15`
- Caracteres extraidos: `231`

#### Texto verificable extraido del PDF

```text
Val
  uePr
     oposi
         ti
          onHeadl
                ine
      Quest
          ion?
  Thi
    sshoul
         dtakel
              esst
                 han3mi
                      nut
                        es
```

#### Lectura verificable del archivo

- El PDF devuelve muy poco texto, lo que confirma que se trata principalmente de un wireframe visual. Las pocas etiquetas extraidas sirven para ubicar modulos o labels, no para leer copy de negocio completo.
- El archivo comparte familia con `8. Quiz page.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

## Familia 9: Lead generation page

Bloque de archivos asociado a `Lead generation page`. Se listan primero los videos y luego los PDFs de la misma familia.

### 9. Lead generation page.mp4

- Tipo MIME: `video/mp4`
- Tamano declarado en Drive: `51.6 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1JsnaDRPtCf0KNHiQ_iunEl92a0O9P46J`
- Duracion real detectada: `324.5 s`
- Idioma detectado en la transcripcion: `en` (0.97)
- Segmentos transcritos: `74`
- Fotogramas de control generados: `start`, `mid`, `end`

#### Hallazgos verificables del audio

- Okay, the Legion wire frame and again we've kind of covered this in the design module I've been through forms etc so I'm not gonna touch on it too much and more gonna touch on kind of the layout and and how I would have this kind of all I'm folding so again ab

#### Extracto de transcripcion

```text
Okay, the Legion wire frame and again we've kind of covered this in the design module
I've been through forms etc so I'm not gonna touch on it too much and more
gonna touch on kind of the layout and and how I would have this kind of all I'm
folding so again above the fold is really important let's cut this off here and
let's say this is the above the fold on our desktop on Legion company logo here
I wouldn't have any internal links if if you do have links in your navigation just
link them to sections on the page anything else as a distraction we've done this
here to showcase some form of social proof and trust so whether that's like SSL
security whether that's an award you've won something or some little icons and
logos that symbolize okay I can trust these guys and I can therefore give them my
information on the form cool to action if needs be which again we just scroll to your
form and then our famous trust policy bar so when it comes to Legion what can we
add here we've helped x amount of cases we we keep all your information safe and
secure social proof whatever it may be that makes you a trusted and
credible company use icons use text and have that kind of policy bar across the
top looking at the left hand side I would always typically lay out like this
left and right split always have your as you look at your website always have
your form on the right hand side but this focus on this left hand side social proof
something that doesn't get used enough when it comes to Legion generation so you
know 4.8 out of 5 stars by a thousand plus happy customers a thousand plus
fathers who secure their families life ensure it's whatever that may be
get a motive with it okay we then have that value driven benefit which again
we've kind of taught you in previous lessons a little
```

### 9.1 Leadgen - desktop.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `1.1 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1P5LqarB5y_seNdMe9MnZCoOlMfODWYpb`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `0`
- Caracteres extraidos: `1`

#### Texto verificable extraido del PDF

No se extrajo texto legible por `pdftotext`. Esto indica que el archivo es mayormente visual o que el texto no esta disponible como capa seleccionable.

#### Lectura verificable del archivo

- Este PDF no aporto texto seleccionable. La señal verificable queda limitada a su existencia dentro de la familia `Lead generation page` y al video homonimo que explica esa misma estructura.
- El archivo comparte familia con `9. Lead generation page.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

### 9.2 Leadgen - mobile.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `369 KB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1qqFqeseDtBvgf-LwgO14p6eQ72yTf2WL`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `0`
- Caracteres extraidos: `1`

#### Texto verificable extraido del PDF

No se extrajo texto legible por `pdftotext`. Esto indica que el archivo es mayormente visual o que el texto no esta disponible como capa seleccionable.

#### Lectura verificable del archivo

- Este PDF no aporto texto seleccionable. La señal verificable queda limitada a su existencia dentro de la familia `Lead generation page` y al video homonimo que explica esa misma estructura.
- El archivo comparte familia con `9. Lead generation page.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

## Familia 10: Multistep lead generation page

Bloque de archivos asociado a `Multistep lead generation page`. Se listan primero los videos y luego los PDFs de la misma familia.

### 10. Multistep lead generation page.mp4

- Tipo MIME: `video/mp4`
- Tamano declarado en Drive: `42.9 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1mgneSMxHrzddV0kMTrJlKlaAh3AoLZyq`
- Duracion real detectada: `265.7 s`
- Idioma detectado en la transcripcion: `en` (0.97)
- Segmentos transcritos: `50`
- Fotogramas de control generados: `start`, `mid`, `end`

#### Hallazgos verificables del audio

- Okay, so the multi step wire frame for lead generation and when you would choose a multi step over the single or one two step form lead generation page is When you want to gamify the whole experience now typically this would be if you have to ask a lot of ques
- They're gonna think I don't want to fill in this whole long form I just want to I just want to get too quickly as possible to the outcome Okay, so this is why you would use something like a multi step because you just gamify it You make it as easy as possible 
- It's really easy for them to click and engage with your form and before you know it There are questions six because they're just going multiple choice multiple choice and it's not until the end of the form That you really ask for a little bit more information 
- So it's not like enter email But it's not like we need your email it's like where would you like us to send your free quote today?
- Please enter the best possible email so that's really important But when it comes to multi step keep it as concise as possible You notice that pretty much everything you know bar this is above the fold on desktop same on mobile Make sure you have that form abo

#### Extracto de transcripcion

```text
Okay, so the multi step wire frame for lead generation and when you would choose a multi step over the single or one two step form lead generation page is
When you want to gamify the whole experience now typically this would be if you have to ask a lot of questions
Because if you had to ask let's say 15 questions and you just put them on one long form
You're gonna turn people away people are gonna get frustrated. They're gonna think I don't want to fill in this whole long form
I just want to I just want to get too quickly as possible to the outcome
Okay, so this is why you would use something like a multi step because you just gamify it
You make it as easy as possible for people to answer a question for example instead of having a long form
The answer question are you may at all female you can just show two options
They click the button especially on mobile. It's really easy for them to click and engage with your form and before you know it
There are questions six because they're just going multiple choice multiple choice and it's not until the end of the form
That you really ask for a little bit more information as far as contact me tells exception
Now when you do that you have to put it as a convenience to the consumer
So you take them through the form and then you get to step eight or whatever it may be and then you position it as if it's
Convenient so it's thank you for filling in the information so far
In order for us to get you your free quote
Where would you like it us to send it to today? So it's not like enter email
But it's not like we need your email it's like where would you like us to send your free quote today?
Please enter the best possible email so that's really important
But when it comes to multi step keep it as concise as possible
You notice that pret
```

### 10.1 Multistep lead generation - desktop.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `670 KB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1QcAGRaVlE2ep7o1A85qTa9rJuhPkT-_6`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `0`
- Caracteres extraidos: `1`

#### Texto verificable extraido del PDF

No se extrajo texto legible por `pdftotext`. Esto indica que el archivo es mayormente visual o que el texto no esta disponible como capa seleccionable.

#### Lectura verificable del archivo

- Este PDF no aporto texto seleccionable. La señal verificable queda limitada a su existencia dentro de la familia `Multistep lead generation page` y al video homonimo que explica esa misma estructura.
- El archivo comparte familia con `10. Multistep lead generation page.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

### 10.2 Multistep lead generation - mobile.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `466 KB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1j70glO_llNDSAM1KLDQO0VZKAJFlOZmL`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `0`
- Caracteres extraidos: `1`

#### Texto verificable extraido del PDF

No se extrajo texto legible por `pdftotext`. Esto indica que el archivo es mayormente visual o que el texto no esta disponible como capa seleccionable.

#### Lectura verificable del archivo

- Este PDF no aporto texto seleccionable. La señal verificable queda limitada a su existencia dentro de la familia `Multistep lead generation page` y al video homonimo que explica esa misma estructura.
- El archivo comparte familia con `10. Multistep lead generation page.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

## Familia 11: Opt-In pages

Bloque de archivos asociado a `Opt-In pages`. Se listan primero los videos y luego los PDFs de la misma familia.

### 11. Opt-In pages.mp4

- Tipo MIME: `video/mp4`
- Tamano declarado en Drive: `42.2 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1x_6zrNS-gJyi3NFV8TfjfMJJRDg0IyQA`
- Duracion real detectada: `270.2 s`
- Idioma detectado en la transcripcion: `en` (0.87)
- Segmentos transcritos: `43`
- Fotogramas de control generados: `start`, `mid`, `end`

#### Hallazgos verificables del audio

- These pages are typically used for anything that just requires basic information.
- So name, email, I kind of would stop there.
- The more questions you ask, the more information you ask from a code click, the less people are going to fill in these pages.
- Okay, so you want to keep the kind of ask or the want on your side, to a bare minimum, so more people are likely to fill them in.
- Now we've tested all different types sorts of opt-in pages, long form, short form above the fold.

#### Extracto de transcripcion

```text
Okay, so opt-in pages. These pages are typically used for anything that just requires basic information.
So name, email, I kind of would stop there. The more questions you ask, the more information you ask from a code click,
the less people are going to fill in these pages. Okay, so you want to keep the kind of ask or the want on your side,
to a bare minimum, so more people are likely to fill them in. Now we've tested all different
types sorts of opt-in pages, long form, short form above the fold. This wire frame converts
better than anything I've ever used, keeping it all within one frame. So what that means is when
someone loads, they can't even scroll. There's nothing to scroll to. Okay, and this is when I said
within the page layouts, there are certain page types that actually don't follow that whole kind of
ADA adapted principle and framework. This is one of them. Keep it real concise. Okay, so as I walk you through
this, we have the website logo or name. Always always showcase your social proof. So let's say this
is an opt-in for a free course. Okay, rated 4.8 out of 5 stars by 100 plus happy students. Okay,
value proposition driven benefit, a benefit driven value proposition headline. So again, just
mentioning the outcome of what they're going to get if they opt-in. So again, if this is a newsletter,
let's say for conversion rate optimization tips and tricks, what's the outcome? Okay,
skyrocket your conversion rates with our free weekly newsletter. Just explain exactly what's
going to happen. Support that with benefit driven bullet points, use emojis or bullets to separate
these and keep it between 3 and 5, 3 probably converts better and make it scanable. So
bold some key phrases within there. Just mention again the benefits or the outcome of opt-in.
If it's a co
```

### 11.1 Opt in - desktop.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `1.6 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1fpnwO3E5gp_sTdTSZF3jMzN8QYXY02S8`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `16`
- Caracteres extraidos: `173`

#### Texto verificable extraido del PDF

```text
Websi
    t
    ename
      4.
       8/5
Val
  uePropos
         it
          ionFeat
                uri
                  ng
Benef
    i
    t
Websi
    tename
```

#### Lectura verificable del archivo

- El PDF devuelve muy poco texto, lo que confirma que se trata principalmente de un wireframe visual. Las pocas etiquetas extraidas sirven para ubicar modulos o labels, no para leer copy de negocio completo.
- El archivo comparte familia con `11. Opt-In pages.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

### 11.2 Opt in - mobile.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `2.6 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1JYgnBNSV6MeVJMloSXh2wIaVWAowbqK8`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `14`
- Caracteres extraidos: `197`

#### Texto verificable extraido del PDF

```text
Websi
         tename
     4.
      8/5
Val
  uePr
     oposit
          ionFeat
                uri
                  ng
       Benefi
            t
        Websi
            tename
```

#### Lectura verificable del archivo

- El PDF devuelve muy poco texto, lo que confirma que se trata principalmente de un wireframe visual. Las pocas etiquetas extraidas sirven para ubicar modulos o labels, no para leer copy de negocio completo.
- El archivo comparte familia con `11. Opt-In pages.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

### 11.3 Opt in modal - desktop.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `1.7 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1qkjjlBfBxJz9-j0oLA9HxpDugkdqgZ85`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `24`
- Caracteres extraidos: `395`

#### Texto verificable extraido del PDF

```text
Websi
    t
    ename
      4.
       8/5
Val
  uePropos
         it
          ionFeat
                uri
                  ng
               Headl
                   inegoesher
                            e
Benef
    i
    t
                 Ent
                   ery
                     ouremai
                           lAddr
                               ess
Websi
    tename
```

#### Lectura verificable del archivo

- El PDF devuelve muy poco texto, lo que confirma que se trata principalmente de un wireframe visual. Las pocas etiquetas extraidas sirven para ubicar modulos o labels, no para leer copy de negocio completo.
- El archivo comparte familia con `11. Opt-In pages.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

### 11.4 Opt in modal - mobile.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `1.5 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1-0Wp_6gbzDg-kYUXsKpOQ-l_mendTahC`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `21`
- Caracteres extraidos: `313`

#### Texto verificable extraido del PDF

```text
Websi
         tename
     4.
      8/5
Val
  uePr
     oposit
          ionFeat
                uri
                  ng
       Benefi
            t
    Headl
        i
        negoesher
                e
        Ent
          ery
            ouremai
                  lAddr
                      ess
```

#### Lectura verificable del archivo

- El PDF devuelve muy poco texto, lo que confirma que se trata principalmente de un wireframe visual. Las pocas etiquetas extraidas sirven para ubicar modulos o labels, no para leer copy de negocio completo.
- El archivo comparte familia con `11. Opt-In pages.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

## Familia 12: Top X page

Bloque de archivos asociado a `Top X page`. Se listan primero los videos y luego los PDFs de la misma familia.

### 12. Top X page.mp4

- Tipo MIME: `video/mp4`
- Tamano declarado en Drive: `57.5 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1koNikTHP_Zl7xQ6AbMPU-ec8iu3755wG`
- Duracion real detectada: `341.8 s`
- Idioma detectado en la transcripcion: `en` (0.93)
- Segmentos transcritos: `42`
- Fotogramas de control generados: `start`, `mid`, `end`

#### Hallazgos verificables del audio

- So, the top X or some people call these review pages, comparison pages, these are not to be confused with listicles.
- Yes, they are in this format, but they are not the same going watch the listicle wire frame breakdown if you want to use a listicle.
- What these pages are, they are exactly the same as far as they are pre-cell, so they help pre-cell your product.
- But what they do is they compare your products against other products that are on the market and in a very subtle, or maybe non-suttle way, they suggest your product is the best versus its competitors.
- So, you can actually run these as a fillet, if, for example, you're getting a fillet commission on other people's products, or you can kind of buy a third party site where you can review your products, like I said, against your competitors.

#### Extracto de transcripcion

```text
So, the top X or some people call these review pages, comparison pages, these are not to be confused with listicles.
Yes, they are in this format, but they are not the same going watch the listicle wire frame breakdown if you want to use a listicle.
What these pages are, they are exactly the same as far as they are pre-cell, so they help pre-cell your product.
But what they do is they compare your products against other products that are on the market and in a very subtle,
or maybe non-suttle way, they suggest your product is the best versus its competitors.
So, you can actually run these as a fillet, if, for example, you're getting a fillet commission on other people's products,
or you can kind of buy a third party site where you can review your products, like I said, against your competitors.
But the real important thing here, as it is any pre-cell, avatoryl's, listicles, those types of pages,
is to make it feel as organic and authentic as possible.
We want people to think that this is, or there should be a kind of an actual site that sits in between ad and sales page,
that just gives an unbiased opinion on a certain list of comparable products.
So, benefit driven headline, typically this is something like top 10 vitamin pills,
then we have an explanation that would go into detail, something around, you know,
if I was writing this article, for example, on the top 10 conversion optimization agencies,
I would say something like, I'm Oliver, I spent 10 years working with various different conversion
radiancies, I have listed the top 10 for you in order based on my personal experience.
Okay, do you want to tell a real story, an authentic story?
Hence, why this is super important to have a picture of the author, the author's name,
so first, that second name, and then a dyn
```

### 12.1 Top X page - desktop.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `23.6 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1jENS04ozcZx8s8zLb8XT_NJV_cavt6h_`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `158`
- Caracteres extraidos: `4315`

#### Texto verificable extraido del PDF

```text
Headl
    ine
Label
                         Soci
                            alPr
                               oof
                                     Pr
                                      ice
               Headl
                   ine
1       Logo                         $$$
                          9.
                          1
                           8
                          00Rat
                              ings
Label
                         Soci
                            alPr
                               oof
                                     Pr
                                      ice
               Headl
                   ine
2       Logo                         $$$
                          9.
                          1
                           8
                          00Rat
                              ings
Label
                         Soci
                            alPr
                               oof
                                     Pr
                                      ice
               Headl
                   ine
3       Logo                         $$$
                          9.
                          1
```

#### Lectura verificable del archivo

- El PDF si aporta texto util: botones, labels, encabezados o microcopy de la maqueta. Eso permite verificar estados, CTA, labels de formulario o estructura de catalogo segun la familia.
- El archivo comparte familia con `12. Top X page.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

### 12.2 Top X page - mobile.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `1.7 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `16P4jC8uy0wy38T8-HwK2wwP45aFelEKO`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `0`
- Caracteres extraidos: `1`

#### Texto verificable extraido del PDF

No se extrajo texto legible por `pdftotext`. Esto indica que el archivo es mayormente visual o que el texto no esta disponible como capa seleccionable.

#### Lectura verificable del archivo

- Este PDF no aporto texto seleccionable. La señal verificable queda limitada a su existencia dentro de la familia `Top X page` y al video homonimo que explica esa misma estructura.
- El archivo comparte familia con `12. Top X page.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

## Familia 13: VSL page

Bloque de archivos asociado a `VSL page`. Se listan primero los videos y luego los PDFs de la misma familia.

### 13. VSL page.mp4

- Tipo MIME: `video/mp4`
- Tamano declarado en Drive: `45.5 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `11cWRPlWkcfLPQTLfc6L2V5mBfv9k_Ncw`
- Duracion real detectada: `299.5 s`
- Idioma detectado en la transcripcion: `en` (0.88)
- Segmentos transcritos: `60`
- Fotogramas de control generados: `start`, `mid`, `end`

#### Hallazgos verificables del audio

- Now, yes, this page focuses heavily on the video itself.
- So, this is arguably the most important part of the page.
- It's a video script that is recorded, that basically takes you to a story about your service, your solution, your product, and why people should buy or work with you.
- However, you can get these pages very wrong as far as layout and elements, and this is the best way to lay them out.
- We focus on that famous benefit driven headline.

#### Extracto de transcripcion

```text
So, the VSL or video cell letter.
Now, yes, this page focuses heavily on the video itself.
So, this is arguably the most important part of the page.
It's a video script that is recorded, that basically takes you to a story about your service, your solution, your product, and why people should buy or work with you.
Based on that video. However, you can get these pages very wrong as far as layout and elements, and this is the best way to lay them out.
So, we start above the fold.
We focus on that famous benefit driven headline.
So, we mention the outcome here.
So, mention that, let's say you're a service or agency, because these work very well for those type of offers,
mention the outcome.
So, mention the benefit, the kind of transformation of the outcome when it comes to work and with your solution.
So, don't just have a generic headline like, we are the best conversion rate agency.
No, say something like, we will generate you more profit per click on your store.
Okay? Then have to be a cell.
Really, importantly, this VSL should be above the fold or mobile and desktop.
It should all play, but it should be muted.
Okay? All to play, but muted.
Below your VSL, support it with some social proofs, so that famous review, a call to action, again stands out and really importantly, keeping it direct response.
So, what is the next step?
Is it to purchase? Is it to join a webinar? Is it to book in a call with you?
Only mention that on here.
Typically, these are used for like agencies and services. So it's nice if you can to anchor it with trust.
I've given an example here of a guarantee. It might be like, you know, double your profits in 90 days or your money back, whatever that may be.
We then have our sort of famous trust bars, bars, bars, brands that we've worked with or done th
```

### 13.1 VSL - desktop.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `3.6 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1_ObLFXeGXdfJbv0a9UKfGNWJwwhLbP-b`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `0`
- Caracteres extraidos: `1`

#### Texto verificable extraido del PDF

No se extrajo texto legible por `pdftotext`. Esto indica que el archivo es mayormente visual o que el texto no esta disponible como capa seleccionable.

#### Lectura verificable del archivo

- Este PDF no aporto texto seleccionable. La señal verificable queda limitada a su existencia dentro de la familia `VSL page` y al video homonimo que explica esa misma estructura.
- El archivo comparte familia con `13. VSL page.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

### 13.2 VSL - mobile.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `1.2 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1PFRBYh_EVBKj-1I5xc5iKl8oxUuUz-ut`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `0`
- Caracteres extraidos: `1`

#### Texto verificable extraido del PDF

No se extrajo texto legible por `pdftotext`. Esto indica que el archivo es mayormente visual o que el texto no esta disponible como capa seleccionable.

#### Lectura verificable del archivo

- Este PDF no aporto texto seleccionable. La señal verificable queda limitada a su existencia dentro de la familia `VSL page` y al video homonimo que explica esa misma estructura.
- El archivo comparte familia con `13. VSL page.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

## Familia 14: Webinar

Bloque de archivos asociado a `Webinar`. Se listan primero los videos y luego los PDFs de la misma familia.

### 14. Webinar.mp4

- Tipo MIME: `video/mp4`
- Tamano declarado en Drive: `55.1 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1d1PGXamaXlt5b1kuUIyPxZmjCghvF4T9`
- Duracion real detectada: `353.2 s`
- Idioma detectado en la transcripcion: `en` (0.88)
- Segmentos transcritos: `66`
- Fotogramas de control generados: `start`, `mid`, `end`

#### Hallazgos verificables del audio

- Now what I would say with Webinar pages is I would always split test meaning put 50% of traffic to this, put 50% of traffic to that with our framework of an opt-in page.
- It depends on the type of consumers you are targeting.
- It depends on the information you want to capture.
- For example, if it's an instant Webinar where the replay plays super super quickly and you just want to capture the name and email, I would probably lean more towards using the opt-in web, why frame for your webinar.
- But if it's a webinar that you require more information from a person, maybe some pre kind of asked questions or phone number, etc, then I would definitely lean towards this webinar page.

#### Extracto de transcripcion

```text
Okay, so Webinar pages. Now what I would say with Webinar pages is I would always
split test meaning put 50% of traffic to this, put 50% of traffic to that with
our framework of an opt-in page. It depends on the type of consumers you are targeting.
It depends on the information you want to capture. For example, if it's an instant
Webinar where the replay plays super super quickly and you just want to capture
the name and email, I would probably lean more towards using the opt-in web, why
frame for your webinar. But if it's a webinar that you require more information from a
person, maybe some pre kind of asked questions or phone number, etc, then I would
definitely lean towards this webinar page. This is a traditional type of webinar
page for kind of more traditional webinars where you actually book in a
kind of time in the future or you know if you have to ask more questions or based
on your demographic. If you're like a say, if you're targeting marketers who just
want to quick fix on a real easy course versus targeting people who in the
financial space who wants something a little bit more professional and are
expecting to be asked questions because it's all about investment and
financials, etc, then this may be the way to go. But always split the two.
Webinar where frame, keep it simple. We have our logo above the fold. We don't have
any navigation's no traffic leaks. Social proof around the outcome of the
webinar. So for example, if this is about investing, 4.8 are 5 stars by 100 plus
happy investors, profitable investors. Headline, let mentioned the value proposition
and benefit. So this is what you're going to get out of the webinar, investing,
learn how to invest and triple your net worth. Things, something like that. Often
you'll need to be a little bit descripti
```

### 14.1 Webinar - desktop.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `6.7 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1AbqobpGkoQZrwYoa92hs5BVzdwgr-Zgo`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `18`
- Caracteres extraidos: `453`

#### Texto verificable extraido del PDF

```text
Websi
                 teLogo
                          Fi
                           rstName
Headl
    ine
                          LastName
                          Emai
                             l
                          Quest
                              ion?
            Beneﬁt
                 s&Feat
                      ures
                      Beneﬁt
                           s
  Feat
     ures
```

#### Lectura verificable del archivo

- El PDF devuelve muy poco texto, lo que confirma que se trata principalmente de un wireframe visual. Las pocas etiquetas extraidas sirven para ubicar modulos o labels, no para leer copy de negocio completo.
- El archivo comparte familia con `14. Webinar.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

### 14.2 Webinar - mobile.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `1.7 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1V9YOXTbqy9qBxDEcPVun20WIlkq2s2iN`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `18`
- Caracteres extraidos: `187`

#### Texto verificable extraido del PDF

```text
Websi
       teLogo
   Headl
       ine
 Fi
  rstName
 LastName
 Emai
    l
 Quest
     ion?
Beneﬁt
     s&Feat
          ures
Beneﬁt
     s
Feat
   ures
```

#### Lectura verificable del archivo

- El PDF devuelve muy poco texto, lo que confirma que se trata principalmente de un wireframe visual. Las pocas etiquetas extraidas sirven para ubicar modulos o labels, no para leer copy de negocio completo.
- El archivo comparte familia con `14. Webinar.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

## Familia 15: SaaS

Bloque de archivos asociado a `SaaS`. Se listan primero los videos y luego los PDFs de la misma familia.

### 15. SaaS.mp4

- Tipo MIME: `video/mp4`
- Tamano declarado en Drive: `50 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1-c_GKDgcgCjhjC1W_TX4BAbdidIGhLg_`
- Duracion real detectada: `331.7 s`
- Idioma detectado en la transcripcion: `en` (0.65)
- Segmentos transcritos: `48`
- Fotogramas de control generados: `start`, `mid`, `end`

#### Hallazgos verificables del audio

- So let's have a look at a typical SAS landing page or homepage, whatever you want to call this.
- This is the framework that I would use if I was advertising or selling a SAS.
- So the framework does follow our kind of perfect page layout if you refer back to that lesson inside the design module.
- Again, depending on this, this is a landing page, dedicated one page or for paid media or a homepage.
- These links would link to sections within the fold or into a terminal pages, but I would keep these very, very short and sweet.

#### Extracto de transcripcion

```text
So let's have a look at a typical SAS landing page or homepage, whatever you want to call this.
This is the framework that I would use if I was advertising or selling a SAS.
So the framework does follow our kind of perfect page layout if you refer back to that lesson inside the design module.
Again, depending on this, this is a landing page, dedicated one page or for paid media or a homepage.
These links would link to sections within the fold or into a terminal pages, but I would keep these very, very short and sweet.
A lot of people just want to see pricing when it comes to SAS, so I would focus on those type of stuff.
On left-hand side, we follow our framework so we have social proof, so we're rating.
Now, it's important when it comes to this rating within SAS that you lean into platforms where ratings are authoritative.
What I mean by that is things like G2, for example, where people go to get ratings on SAS.
If you use generic icons and emojis, fine, but it's going to hold a lot more weight if you use something like that sort of platform.
Value driven value proposition here, so maintaining the outcome, the transformation, the results you're going to deliver with your SAS.
And then benefit driven bullet points. These should focus primarily on the time and money you're going to save people to effectively replace what they're going to have to do via with software.
So software is typically making kind of mundane things easier, more affordable and systematized.
So focus on that use bullet points, use icons and bolt and key phrases.
One call to action, now that could be to book a consultation call, that could be to speak to the enterprise team.
It could be just to go to pricing or it could be to just to sign up.
Whatever works for you, just focus the whole page around tha
```

### 15.1 SaaS - desktop.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `9.1 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1YdVEtinRuQkH99fO926ASDOe1IFNwRRY`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `7`
- Caracteres extraidos: `47`

#### Texto verificable extraido del PDF

```text
Compar
     ison
 Br
  and
 Logo   C1   C2
```

#### Lectura verificable del archivo

- El PDF devuelve muy poco texto, lo que confirma que se trata principalmente de un wireframe visual. Las pocas etiquetas extraidas sirven para ubicar modulos o labels, no para leer copy de negocio completo.
- El archivo comparte familia con `15. SaaS.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

### 15.2 SaaS - mobile.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `2.6 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1qwh42HDNNmUFBm23S8zBltVg8Y2o8CnB`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `6`
- Caracteres extraidos: `47`

#### Texto verificable extraido del PDF

```text
Compar
     ison
   Br
    and
   Logo   C1
```

#### Lectura verificable del archivo

- El PDF devuelve muy poco texto, lo que confirma que se trata principalmente de un wireframe visual. Las pocas etiquetas extraidas sirven para ubicar modulos o labels, no para leer copy de negocio completo.
- El archivo comparte familia con `15. SaaS.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

## Familia 16: Service

Bloque de archivos asociado a `Service`. Se listan primero los videos y luego los PDFs de la misma familia.

### 16. Service.mp4

- Tipo MIME: `video/mp4`
- Tamano declarado en Drive: `49.2 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1LHglzCw2xK1Tc87jBLBT-ARKPbRfDQgr`
- Duracion real detectada: `321.5 s`
- Idioma detectado en la transcripcion: `en` (0.92)
- Segmentos transcritos: `65`
- Fotogramas de control generados: `start`, `mid`, `end`

#### Hallazgos verificables del audio

- Okay, so this is our service wireframe and this sort of page you would use if you're offering a service a solution and agency page maybe I would also make sure you take a look at the VSL breakdown because typically for paid Media and direct response media of V
- I would just have these links, but I would make them scroll to the different sections along that kind of adapted a different Work you have your logo Cool to action really important as I say in the call to action lesson to keep that call to action Consistent bu
- So just tell them that's what you want them to do book in free discovery call now Value proposition mentioning the benefits of headline mentions the outcome of working with you as a solution Social proof instead of a boring description break it down into three
- I worked with X and they generated why okay real picture Real first and last name now.
- This is something I would test as I said the SL's work very very well If you don't want to do a video about the fold then use an image now It depends if you are the service if you are the service then give authority to yourself and make Your business look more

#### Extracto de transcripcion

```text
Okay, so this is our service wireframe and this sort of page you would use if you're offering a service
a solution and agency page maybe I would also make sure you take a look at the VSL breakdown because typically for paid
Media and direct response media of VSL
Pages work very very well for services and agency businesses as well
However if you are like I'll say a service or an agency and you're just looking for something to put up to a
Tract new customers this is the framework I would be using so
We're not kind of reinventing the wheel above the fold here
We have minimal links if I was doing this and I didn't have a full store yet a full site yet
It's a brochure site. I would just have these links, but I would make them scroll to the different sections along that kind of adapted a different
Work you have your logo
Cool to action really important as I say in the call to action lesson to keep that call to action
Consistent but keep it precise what is the one thing you want me to do
Normally as a service of solution is to book in a call. So just tell them that's what you want them to do book in free discovery call now
Value proposition mentioning the benefits of headline mentions the outcome of working with you as a solution
Social proof instead of a boring description break it down into three benefit driven bullet points
One clear call to action that mentions the outcome that you want so book in a free call and back it up with social proof
I had a freeze discovery call. I worked with X and they generated why okay real picture
Real first and last name now. This is something I would test as I said the SL's work very very well
If you don't want to do a video about the fold then use an image now
It depends if you are the service if you are the service then give authority to
```

### 16.1 Service - desktop.pdf

- Tipo MIME: `application/pdf`
- Tamano declarado en Drive: `8 MB`
- Ultima modificacion visible en Drive: `11 abr 2024`
- Google Drive fileId: `1RsNDrNSt7bMT3Iw-n7P6xv8YoIRmDlLt`
- Paginas detectadas: `1`
- Palabras extraidas por `pdftotext`: `14`
- Caracteres extraidos: `251`

#### Texto verificable extraido del PDF

```text
Beneﬁt
               s
Feat
   ures
                   Feat
                      ures
Feat
   ures
                   Feat
                      ures
Feat
   ures
                   Feat
                      ures
```

#### Lectura verificable del archivo

- El PDF devuelve muy poco texto, lo que confirma que se trata principalmente de un wireframe visual. Las pocas etiquetas extraidas sirven para ubicar modulos o labels, no para leer copy de negocio completo.
- El archivo comparte familia con `16. Service.mp4`, cuyo audio explica el objetivo y layout de esta misma pieza.

## Conclusiones del set

- El Drive no contiene material juridico ni institucional; contiene una biblioteca de entrenamiento/referencia para diseñar funnels y landings de conversion.
- Los videos no son solo demos visuales: la mayoria tiene narracion explicativa en ingles que describe por que usar cada tipo de pagina, que elementos poner above the fold y como ordenar CTA, social proof, formularios y comparativas.
- Muchos PDFs son wireframes con muy poca capa de texto. En esos casos, el valor del archivo esta en la estructura visual y el complemento fuerte viene del video de la misma familia.
- Las familias cubren casi todo el recorrido de conversion: home, product, collections, cart, sales, pre-sell, quiz, leadgen, opt-in, VSL, webinar, SaaS y service pages.

