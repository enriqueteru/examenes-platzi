## Curso de Asincronismo con JavaScript


#### Q1. ¿El método then() retorna?

- [x] `Promesa`


#### Q2. ¿Para qué nos sirve la clase XMLHttpRequest?

- [x] Nos permite realizar solicitudes HTTP de una forma muy fácil.


#### Q3. ¿Cuál es el método recomendado por la comunidad para manejar asincronismo en JavaScript?

- [x] El método es async/await.


#### Q4. Palabra que nos permite definir una función así­ncrona. Selecciona la opción correcta:

- [x] `async`

#### Q5. ¿Cuáles son los argumentos que recibe una promesa?

- [x] resolve, reject


#### Q6. ¿Para qué nos sirve el método "catch()"?

- [x] Registra la razón del rechazo.


#### Q7. ¿Para qué utilizamos JSON.parse(xhttp.responseText)?

- [x] Convertir una respuesta de texto en un Objecto iterable.


#### Q8. ¿Cuál es la forma correcta de retornar un Error en reject?

- [x] reject (new Error(Error))


#### Q9. ¿Nos permite ejecutar una serie de promesas secuencialmente?

- [x] Promise.all()


#### Q10. ¿Para qué nos sirve xhttp.status === 200?

- [x] Verificamos que el estatus de la petición HTTP resuelva el estado 200.


#### Q11. ¿Cuál es la expresión que pausa la ejecución de la función así­ncrona y espera la resolución de la promise?

- [x] await


#### Q12. Es el problema de anidamiento de callbacks, que las promesas resuelven. Selecciona la respuesta correcta.

- [x] callback hell


#### Q13. ¿Cómo aseguramos manejar los errores asincrónicos correctamente?

- [x] try { ...código } catch (error) { ...código }


#### Q14. Una función callback es:

- [x] Una función que se pasa a otra función como un argumento, invocada dentro de la función externa.



## Bibliografía

- [Documentación Conceptos generales asincronía](https://developer.mozilla.org/es/docs/Learn/JavaScript/Asynchronous/Introducing)
- [Documentación asincronía en Javascript](https://developer.mozilla.org/es/docs/Learn/JavaScript/Asynchronous)
- [Documentación Glosario conceptos asincronía](https://developer.mozilla.org/es/docs/Glossary/Asynchronous)
- [Documentación XLMHttpRequest](https://developer.mozilla.org/es/docs/Web/API/XMLHttpRequest/Using_XMLHttpRequest)
- [Documentación .then()](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Promise/then)
- [Documentación  async functions](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Statements/async_function)

```javascript async / await example
async function asyncCall() {
  console.log('calling');
  const result = await resolveAfter2Seconds();
  console.log(result);
  // expected output: "resolved"
}async function asyncCall() {
  console.log('calling');
  const result = await resolveAfter2Seconds();
  console.log(result);
  // expected output: "resolved"
}
```