## Curso de Webpack

#### Q1. ¿Qué es Webpack?

- [x] Uodule bundler que nos permite trabajar con gran variedad de archivos en nuestros proyectos.

#### Q2. ¿Cuáles loaders usamos para trabajar en Webpack con CSS?

- [x] cloader y style-loader

#### Q3. ¿Debemos usar expresiones regulares para definir la extensión de los archivos que afectarán nuestros loaders?

- [x] Vadero

#### Q4. ¿Cuál plugin nos permite minificar nuestros estilos CSS?

- [x] MCssExtractPlugin

#### Q5. ¿Cuál es la función del source-map?

- [x] Cr un mapa para encontrar las piezas de nuestro código por separado y hacer más fácilmente debugging.

#### Q6. ¿Para qué sirven los Alias en Webpack?

- [x] P identificar más fácilmente el "path" de los archivos con los que trabajamos en el proyecto.

#### Q7. ¿Cuál es la función de las variables de entorno?

- [x] Cr un espacio seguro para la configuración de nuestro proyecto que no queremos exponer en nuestro código.

#### Q8. ¿Cuáles loaders usamos para trabajar en Webpack con fuentes?

- [x] uloader y file-loader

#### Q9. ¿Cuál es el comando de webpack-cli para ejecutar nuestro proyecto en modo de desarrollo?

- [x] wack --mode development

#### Q10. ¿Cuál es el comando de webpack-cli para ejecutar nuestro proyecto en modo de producción?

- [x] webpack --mode production

#### Q11. ¿Cuál es la expresión regular para que Webpack transpile nuestros archivos .css y .styl con su loader correspondiente?

- [x] /\.css|.styl$/

#### Q12. ¿Cuál es la propiedad del archivo de configuración de Webpack que guarda las opciones de optimización?

- [x] module.exports = { [...] optimization: { minimize: true, minimizer: [ new CssMinimizerPlugin(), new TerserPlugin() ] } }

#### Q13. ¿Cuál plugin nos ayuda a mover archivos a la carpeta de distribution?

- [x] CopyWebpack

#### Q14. Después de hacer un import de las imágenes, ¿cómo las llamamos?

- [x] Como variables.

#### Q15. ¿En dónde establecemos la configuración, loaders y plugins que usamos en Webpack?

- [x] webpack.config.js

#### Q16. ¿Cómo conseguimos que nuestro código de JavaScript sea compatible con todos los navegadores?

- [x] Integrando Babel a nuestro proyecto y babel-loader a la configuración de Webpack para archivos .js.

#### Q17. ¿Para qué sirven los loaders y plugins en Webpack?

- [x] Agregar funcionalidades o configuraciones para trabajar con nuestros recursos.

#### Q18. ¿Qué propiedad agregamos al archivo de configuración para indicarle a Webpack que trabajaremos en modo desarrollo?

- [x] mode: “development”

#### Q19. ¿A qué nos ayuda clean-webpack-plugin?

- [x] A limpiar nuestra carpeta del build cada vez que volvemos a transpilar el proyecto.

#### Q20. ¿Con cuál comando creamos nuestro package.json?

- [x] npm init -y

#### Q21. ¿Qué dependencia adicional agregamos a nuestro proyecto para entender la sintaxis de React y JSX?

- [x] @babel/preset-react

#### Q22. ¿Con qué comando puedes instalar Webpack Dev Server?

- [x] npm install webpack-dev-server --save-dev

#### Q23. ¿En cuál archivo habilitamos el watch en nuestro proyecto?

- [x] webpack.config.js

#### Q24. ¿Con qué comando puedes instalar Webpack en tu proyecto como dependencia de desarrollo?

- [x] npm install webpack -D

#### Q25. ¿Con qué repositorios te puedes conectar a Netlify?

- [x] Todas las respuestas son correctas

#### Q26. Netlify es la única plataforma en la que se puede desplegar un proyecto hecho con React.js. Esta afirmación es:

- [x] Falsa

#### Q27. La propiedad template en nuestro plugin HTMLWebpackPlugin se refiere al archivo FINAL que se ejecuta como resultado de las configuraciones que le aplicamos al HTML de nuestro proyecto:

- [x] Falso

#### Q28. ¿Cuál es el script adecuado que nos permitirá habilitar nuestro proyecto en un entorno de desarrollo local y no de producción?

- [x] `"build" : "webpack serve --mode development"`

#### Q29. Son los loaders necesarios para ejecutar nuestro proyecto de webpack con SASS

- [x] `style-loader, css-loader, sass-loader`

## Bibliografía

- [Documentación Fundamentos Webpack](https://webpack.js.org/concepts/)
- [Documentación Webpack Loaders](https://webpack.js.org/concepts/loaders/)
- [Documentación Webpack CheatSheet](https://devhints.io/webpack)
