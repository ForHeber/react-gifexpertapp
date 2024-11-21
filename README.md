# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)


TITULO_FORMATO = int.TryParse(t.TITULO.Replace(".", ""), out var numero) ? numero : 0, // Elimina puntos y convierte a número

Un árbol de expresión no puede contener una declaración de variable de argumento out. [C:\U


.AsEnumerable() // Procesar en memoria
.Select(t => new
{
    t.ID,
    t.PLANID,
    t.TIPO_TAREAID,
    t.PADREID,
    t.NUMERO,
    t.TIPO_PLANID,
    t.TITULO,
    TITULO_FORMATO = string.Join("", t.TITULO
        .Split('.') // Dividir por puntos
        .Select(part => part.PadLeft(3, '0'))), // Rellenar con ceros a la izquierda
    t.DESCRIPCION,
    t.PROPOSITO,
    t.UNIDADCODIGO,
    t.INICIO,
    t.PLAZO,
    t.PONDERADO,
    t.CUMPLIMIENTO,
    t.CUMPLIMIENTO_REAL,
    t.PLANIFICADO,
    t.ESTADO,
    t.CREACION,
    t.ACTUALIZACION,
    t.NUMERO_DOCUMENTO,
    t.PRIORIDADID,
    t.PRIORIDAD,
    t.UNIDAD,
    t.ORDEN,
    t.TIPO_DOMINIOID,
    t.TIPO_DOMINIO,
    t.TAREA,
    t.ESTADOAVANCE,
    t.VALIDACIONES,
    t.UNIDADES_AFECTADAS,
    t.UNIDADAFECTADA,
    t.UNIDADAFECTADA2,
    t.TIPO_TAREA,
    t.ESTADOSITUACION,
    t.ESTADOAVANCESUBTAREAPENDIENTE,
    t.ESTADOAVANCESUBTAREAVALIDADO,
    t.AJUSTESPENDIENTES,
    t.AJUSTESPENDIENTESVALIDACION,
    t.AJUSTESRECHAZADOS,
    t.NOTIFICACIONNUEVA,
    t.CIERRETAREA
})
.OrderBy(t => t.TITULO_FORMATO) // Ordenar por el formato ajustado
.ToList();
.OrderBy(t => t.TITULO_FORMATO)
.ToList();


The source 'IQueryable' doesn't implement 'IAsyncEnumerable<<>f__AnonymousType55`42[System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,Sidce.Entidades.Tareas.Plan,System.String,System.String,System.String,System.String,System.String,System.Nullable`1[System.DateTime],System.Nullable`1[System.DateTime],System.Single,System.Single,System.Single,System.Single,System.Int32,System.DateTime,System.DateTime,System.String,System.Int32,<>f__AnonymousType37`2[System.Int32,System.String],Sidce.Entidades.EntidadesInstitucionales.Unidad,System.Int32,System.Int32,Sidce.Entidades.Mantenedores.Tipo_Dominio,System.Int32,System.Int32,System.Int32,System.Collections.Generic.List`1[Sidce.Entidades.Tareas.Tarea_Afecta_Unidad],System.Collections.Generic.List`1[Sidce.Entidades.EntidadesInstitucionales.Unidad],Sidce.Entidades.Tareas.Tarea_Afecta_Unidad,Sidce.Entidades.Mantenedores.Tipo_Tarea,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32]>'. Only sources that implement 'IAsyncEnumerable' can be used for Entity Framework asynchronous operations.
