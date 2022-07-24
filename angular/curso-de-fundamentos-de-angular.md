## Curso de fundamentos de angular

#### Q1. ¿Cuál es el comando para instalar el Angular CLI?

- [x] npm i @angular/cli -g

#### Q2. ¿Cuál es el comando correcto para correr un proyecto en Angular en forma de desarrollo y en el puerto 3009?

- [x] ng serve --port=3009

#### Q3. ¿Qué función tiene el archivo .browserslistrc ?

- [x] La configuración en donde expresamos que versiones de navegadores vamos a soportar.

#### Q4. En TypeScript, ¿cuál es la forma correcta de 'tipar' una variable?

- [x] const name: string = 'Nicolas';

#### Q5. ¿Cuál de las siguientes expresiones usando String Interpolation da un error?

- [x] {{ Math.pow(2,2) }}

#### Q6. Usando Property Binding, ¿cuál es la forma correcta de controlar el estado ‘disable’ de un botón de un HTML?

- [x] <button [disable]=“btnState”>My Button</button>

#### Q7. ¿Cuál es la forma correcta de llamar un evento click usando Event Binding?

- [x] <button (click)=“doSomething()”>My Button</button>

#### Q8. ¿Cuál sería la forma correcta sin usar ngModel de leer los cambios en un input?

- [x] <input type=“text” [value]=“name” (keyup)=“changeName($event)”>

#### Q9. ¿Cuál paquete de Angular debemos importar en el App Módulo para trabajar con NgModel?

- [x] import { ReactiveFormsModule } from '@angular/forms';

#### Q10. ¿Cuál es la forma correcta de usar un ngIf en el template?

- [x] <p *ngIf=“1 === 1”>My Text</p>

#### Q11. ¿Cuál sería la forma correcta de imprimir este array ['a', 'b', 'c'] en un template usando el ngFor?

- [x] <p *ngFor=“let item of [‘a’, ‘b’, ‘c’]”>{{ item }}</p>

#### Q12. ¿Cuál es la forma correcta de aplicar una clase dinámica con Angular?

- [x] <p [class.myClass]=“1 === 1”>My text</p>

#### Q13. Usando el Property binding, ¿cuál es la forma de modificar el ancho de un elemento?

- [x] <p [style.width.px]=“100”>Text</p>

#### Q14. ¿Cuál es el evento que nos da angular para llamar el sumbit de un formulario?

- [x] <form (ngSubmit)=“onSave()”>Text</form>

#### Q15. ¿Cuál es comando que nos ofrece Angular alistar nuestro proyecto para producción?

- [x] ng build

## Bibliografía

- [Documentación Fundamentos de Angular](https://angular.io/start)
- [Documentación Angular cheat sheet](https://angular.io/guide/cheatsheet)
