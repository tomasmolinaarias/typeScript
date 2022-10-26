# `TYPESCRIPT`

#### ¿que es para que sirve?

TypeScript es usado para desarrollar aplicaciones `JavaScript` que se ejecutarán en el lado del cliente o del servidor, o extensiones para programas `(Node. js y Deno)`.

```
TypeScript extiende la sintaxis de JavaScript,
por tanto cualquier código JavaScript existente debería funcionar sin problemas.
```

#### ¿deferencias de JavaSCript y TypeScript?

TypeScript dispone de una `escritura estática`, mientras que `JavaScript es un lenguaje dinámico`.

```
 JavaScript no admite módulos, mientras que TypeScript sí que les da soporte.
 TypeScript dispone de interfaz, mientras que JavaScript no.
 En TypeScript sí que hay que compilar el código, en JavaScript no es necesario.
```

### para hacer archivos typesciprt

se tiene que instalar paquetes

```
npm install typescript --save-dev
npx tsc --version
```

```
 coloca:
  .ts
  ej: xxxx.ts
```

## para activa test en js

se comenta

```
//@ts-checks
```

sirve para ver bug del lo que llevamos escrito.

### para poder cambiar es5 a es6 con archivo .ts

```
npx tsc ts/archivo.ts  --target es6 --outDir prueba
```

npx y se coloca la direcion del archivo y despues con el target se coloca ecmascript y su version despues con el outDir se coloca donde mandar el archivo
