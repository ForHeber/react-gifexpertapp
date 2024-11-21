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

public class TareaDto
{
    public int ID { get; set; }
    public int PLANID { get; set; }
    public int TIPO_TAREAID { get; set; }
    public int PADREID { get; set; }
    public int NUMERO { get; set; }
    public Plan? TIPO_PLANID { get; set; }
    public string? TITULO { get; set; }
    public string? DESCRIPCION { get; set; }
    public string? PROPOSITO { get; set; }
    public string? UNIDADCODIGO { get; set; }
    public DateTime? INICIO { get; set; }
    public DateTime? PLAZO { get; set; }
    public decimal? PONDERADO { get; set; }
    public decimal? CUMPLIMIENTO { get; set; }
    public decimal? CUMPLIMIENTO_REAL { get; set; }
    public bool? PLANIFICADO { get; set; }
    public int ESTADO { get; set; }
    public DateTime? CREACION { get; set; }
    public DateTime? ACTUALIZACION { get; set; }
    public string? NUMERO_DOCUMENTO { get; set; }
    public int? PRIORIDADID { get; set; }
    public object? PRIORIDAD { get; set; }
    public object? UNIDAD { get; set; }
    public int? ORDEN { get; set; }
    public int? TIPO_DOMINIOID { get; set; }
    public object? TIPO_DOMINIO { get; set; }
    public int TAREA { get; set; }
    public int ESTADOAVANCE { get; set; }
    public int VALIDACIONES { get; set; }
    public List<object>? UNIDADES_AFECTADAS { get; set; }
    public List<object>? UNIDADAFECTADA { get; set; }
    public object? UNIDADAFECTADA2 { get; set; }
    public object? TIPO_TAREA { get; set; }
    public int ESTADOSITUACION { get; set; }
    public int ESTADOAVANCESUBTAREAPENDIENTE { get; set; }
    public int ESTADOAVANCESUBTAREAVALIDADO { get; set; }
    public int AJUSTESPENDIENTES { get; set; }
    public int AJUSTESPENDIENTESVALIDACION { get; set; }
    public int AJUSTESRECHAZADOS { get; set; }
    public int NOTIFICACIONNUEVA { get; set; }
    public int CIERRETAREA { get; set; }
}
