https://www.youtube.com/watch?v=iJKCj8uAHz8          1:45

click derecho --> git bash here
npm init
npm install --save-dev sass
npm install bootstrap --save
npm install --save @fortawesome/fontawesome-free
npm install postcss-cli autoprefixer --save

package.json
	 "scripts": {
    		"compile:sass": "sass --watch scss:assets/css"
  	  },
carpeta scss/style.scss
npm run compile:sass
copiamos theming-kit.html en la carpeta raiz
_custom.css con @import "../node_modules/bootstrap/scss/bootstrap.scss";
style.css con @use 'custom';
node_modules -- bootstrap -- _variables.scss -> costumizar colores primary y secondary y accordion button (imagenes de bootstrap 5 icons)
HTML CODE DEL ICONO:
	<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-plus-circle" viewBox="0 0 16 16">
  	<path d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"/>
  	<path d="M8 4a.5.5 0 0 1 .5.5v3h3a.5.5 0 0 1 0 1h-3v3a.5.5 0 0 1-1 0v-3h-3a.5.5 0 0 1 0-1h3v-3A.5.5 0 0 1 8 4z"/>
	</svg>

	<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-dash-circle" viewBox="0 0 16 16">
  	<path d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"/>
  	<path d="M4 8a.5.5 0 0 1 .5-.5h7a.5.5 0 0 1 0 1h-7A.5.5 0 0 1 4 8z"/>
	</svg>

manypixels.co/gallery ---> Ilusitraciones (images/art)
https://fonts.google.com ---> TIPOGRAFIA	
getwaves.io  ---> efecto olas
https://biati-digital.github.io/glightbox/  ---> descargar y meter css y js dentro de vendors en assets