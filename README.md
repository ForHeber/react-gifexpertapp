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



var tareasMaterializadas = await tareas
    .Select(t => new
    {
        t.ID,
        t.PLANID,
        t.TIPO_TAREAID,
        t.PADREID,
        t.NUMERO,
        t.TIPO_PLANID,
        t.TITULO,
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
    .ToListAsync(); // Ejecuta la consulta asincrónicamente y materializa los datos

// Aplicar transformaciones adicionales en memoria
var tareasTransformadas = tareasMaterializadas
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
    .AsQueryable();

The source 'IQueryable' doesn't implement 'IAsyncEnumerable<<>f__AnonymousType55`42[System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,Sidce.Entidades.Tareas.Plan,System.String,System.String,System.String,System.String,System.String,System.Nullable`1[System.DateTime],System.Nullable`1[System.DateTime],System.Single,System.Single,System.Single,System.Single,System.Int32,System.DateTime,System.DateTime,System.String,System.Int32,<>f__AnonymousType37`2[System.Int32,System.String],Sidce.Entidades.EntidadesInstitucionales.Unidad,System.Int32,System.Int32,Sidce.Entidades.Mantenedores.Tipo_Dominio,System.Int32,System.Int32,System.Int32,System.Collections.Generic.List`1[Sidce.Entidades.Tareas.Tarea_Afecta_Unidad],System.Collections.Generic.List`1[Sidce.Entidades.EntidadesInstitucionales.Unidad],Sidce.Entidades.Tareas.Tarea_Afecta_Unidad,Sidce.Entidades.Mantenedores.Tipo_Tarea,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32]>'. Only sources that implement 'IAsyncEnumerable' can be used for Entity Framework asynchronous operations.



public async Task<ActionResult<List<ResponsePaginationTareaModel>>> GetTareas([FromQuery] int page, int tipo_plan_id, int planid, int tipo_tareaid, int padreid, string? busqueda, string? unidadCodigo, string? unidadfiltro, int? tipoPlanSearch, int? planesSearch, int? prioridadSearch, int? merodisiSearch, DateTime? fechaInicio, DateTime? fechaTermino)
        {
            var nivel = int.Parse(User.GetClaimValue("NivelAcceso"));
            JsonStatusModel resp = new JsonStatusModel();

            try
            {
                var tarea = (
                    from t in _sidcecontext.Tareas
                    where (t.ESTADO == 1 || t.ESTADO == 2 || t.ESTADO == 9 || t.ESTADO == 10) && t.PLANID == 6714
                    select new
                    {
                        ID = t.ID,
                        PLANID = t.PLANID,
                        TIPO_TAREAID = t.TIPO_TAREAID,
                        PADREID = t.PADREID,
                        NUMERO = t.NUMERO,
                        TIPO_PLANID = _sidcecontext.Planes.Where(p => p.ID == t.PLANID).FirstOrDefault(),
                        TITULO = t.TITULO,
                        DESCRIPCION = t.DESCRIPCION,
                        PROPOSITO = t.PROPOSITO,
                        UNIDADCODIGO = t.UNIDADCODIGO,
                        INICIO = t.INICIO,
                        PLAZO = t.PLAZO,
                        PONDERADO = t.PONDERADO,
                        CUMPLIMIENTO = t.CUMPLIMIENTO,
                        CUMPLIMIENTO_REAL = t.CUMPLIMIENTO_REAL,
                        PLANIFICADO = t.PLANIFICADO,
                        ESTADO = t.ESTADO,
                        CREACION = t.CREACION,
                        ACTUALIZACION = t.ACTUALIZACION,
                        NUMERO_DOCUMENTO = t.NUMERO_DOCUMENTO,
                        PRIORIDADID = t.PRIORIDAD,
                        PRIORIDAD = (from tt in _sidcecontext.Tareas
                                     where t.ID == tt.ID
                                     select new
                                     {
                                         ID = tt.PRIORIDAD,
                                         DESCRIPCION = (
                                             tt.PRIORIDAD == 1 ? "Baja" :
                                             tt.PRIORIDAD == 2 ? "Media" :
                                             tt.PRIORIDAD == 3 ? "Alta" : ""
                                         )
                                     }).FirstOrDefault(),
                        UNIDAD = (
                            from u in _sidcecontext.Unidades
                            where u.CODIGO == t.UNIDADCODIGO
                            select u
                        ).FirstOrDefault(),
                        ORDEN = (
                            from pe in _sidcecontext.PlaneEstructuras
                            join p in _sidcecontext.Planes on pe.TIPO_PLANID equals p.TIPO_PLANID
                            where t.PLANID == p.ID && t.TIPO_TAREAID == pe.TIPO_TAREAID
                            select pe.ORDEN
                        ).FirstOrDefault(),
                        TIPO_DOMINIOID = t.TIPO_DOMINIOID,
                        TIPO_DOMINIO = (
                            from d in _sidcecontext.Tipo_Dominios
                            where d.ID == t.TIPO_DOMINIOID
                            select d
                        ).FirstOrDefault(),
                        TAREA = (
                            from t2 in _sidcecontext.Tareas
                            where t.ID == t2.PADREID && (t2.ESTADO == 1 || t2.ESTADO == 2 || t2.ESTADO == 3)
                            select t2
                        ).Count(),
                        ESTADOAVANCE = (
                            from ea in _sidcecontext.Estados_Avance
                            where t.ID == ea.TAREAID && (ea.ESTADO == 2 && ea.TIPO_ENTIDADID == 1)
                            select ea
                        ).Count(),
                        VALIDACIONES = (
                            from ea in _sidcecontext.Estados_Avance
                            join v in _sidcecontext.Validaciones on ea.ID equals v.ENTIDADID
                            where t.ID == ea.TAREAID && (ea.ESTADO == 2 && ea.TIPO_ENTIDADID == 1) && v.ESTADO == 4
                            select ea
                        ).Count(),
                        UNIDADES_AFECTADAS = (
                            _sidcecontext.Tarea_Afecta_Unidad.Where(TAU => TAU.TAREAID == t.ID && TAU.ESTADO == 1)
                        ).ToList(),
                        UNIDADAFECTADA = (
                            from u in _sidcecontext.Unidades
                            join tau in _sidcecontext.Tarea_Afecta_Unidad on u.CODIGO equals tau.UNIDADCODIGO
                            where t.ID == tau.TAREAID && tau.ESTADO == 1
                            select u
                        ).ToList(),
                        UNIDADAFECTADA2 = (
                            from tu in _sidcecontext.Tarea_Afecta_Unidad
                            join u in _sidcecontext.Unidades on tu.UNIDADCODIGO  equals u.CODIGO
                            where t.ID == tu.TAREAID && tu.ESTADO == 1
                            select tu
                        ).FirstOrDefault(),
                        TIPO_TAREA = (
                            from tt in _sidcecontext.Tipos_Tareas
                            where tt.ID == t.TIPO_TAREAID
                            select tt
                        ).FirstOrDefault(),
                        ESTADOSITUACION = (
                            from ea in _sidcecontext.Estados_Avance
                            join t2 in _sidcecontext.Tareas on ea.TAREAID equals t2.ID
                            where t.ID == t2.PADREID && ((ea.ESTADO == 7  || ea.ESTADO == 8) && ea.TIPO_ENTIDADID == 4) && t2.ESTADO == 1
                            select ea
                        ).Count(),
                        ESTADOAVANCESUBTAREAPENDIENTE = (
                            from ea in _sidcecontext.Estados_Avance
                            join t2 in _sidcecontext.Tareas on ea.TAREAID equals t2.ID
                            join p2 in _sidcecontext.Planes on t2.PLANID equals p2.ID
                            where t.ID == t2.PADREID && ea.TIPO_ENTIDADID == 1 && t2.ESTADO == 1 && ea.ESTADO == 2 && p2.ESTADO == 1
                            select ea
                        ).Count(),
                        ESTADOAVANCESUBTAREAVALIDADO = (
                            from ea in _sidcecontext.Estados_Avance
                            join t2 in _sidcecontext.Tareas on ea.TAREAID equals t2.ID
                            where t2.PADREID == t.ID && ea.TIPO_ENTIDADID == 1 && t2.ESTADO == 1 && ea.ESTADO == 1
                            select ea
                        ).Count()
                        ,
                        AJUSTESPENDIENTES = (
                            from a in _sidcecontext.Ajustes
                            join t2 in _sidcecontext.Tareas on a.TAREAID equals t2.ID
                            join p2 in _sidcecontext.Planes on t2.PLANID equals p2.ID
                            where t.ID == t2.PADREID && t2.ESTADO == 1 && a.ESTADO == 2 && p2.ESTADO == 1
                            select a
                        ).Count(),
                        AJUSTESPENDIENTESVALIDACION = (
                            from v in _sidcecontext.Validaciones
                            join a in _sidcecontext.Ajustes on v.ENTIDADID equals a.ID
                            where t.ID == v.TAREAID && (v.ESTADO == 5 || v.ESTADO == 4 || v.ESTADO == 1) && v.TIPO_ENTIDADID == 2 && (a.ESTADO == 2 || a.ESTADO == 4)
                            select v
                        ).Count(),
                        AJUSTESRECHAZADOS = (
                            from a in _sidcecontext.Ajustes
                            join t2 in _sidcecontext.Tareas on a.TAREAID equals t2.ID
                            join p2 in _sidcecontext.Planes on t2.PLANID equals p2.ID
                            where t.ID == t2.PADREID && t2.ESTADO == 1 && a.ESTADO == 6 && p2.ESTADO == 1
                            select a
                        ).Count(),
                        NOTIFICACIONNUEVA = (
                            from n in _sidcecontext.Notificacion
                            where n.TAREAID == t.ID && n.PROPIETARIO != int.Parse(User.GetClaimValue("Run")) && !(
                                from v in _sidcecontext.Visto
                                where v.USUARIO == int.Parse(User.GetClaimValue("Run"))
                                select v.NOTIFICACIONID
                            ).Contains(n.ID)
                            select n
                        ).Count(),
                        CIERRETAREA = (
                            from v in _sidcecontext.Validaciones
                            where v.ENTIDADID == t.ID && v.TIPO_ENTIDADID == 3 && v.ESTADO == 1
                            select v
                        ).Count(),
                    }
                ).OrderBy(res => res.TITULO).AsQueryable();

                var tareasMaterializadas = await tarea
    .Select(t => new
    {
        t.ID,
        t.PLANID,
        t.TIPO_TAREAID,
        t.PADREID,
        t.NUMERO,
        t.TIPO_PLANID,
        t.TITULO,
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
    .ToListAsync(); // Ejecuta la consulta asincrónicamente y materializa los datos

// Aplicar transformaciones adicionales en memoria
var tareas = tareasMaterializadas
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
    .AsQueryable();



                //Inicio de filtros
                if (!string.IsNullOrWhiteSpace(busqueda))
                {
                    int numero = ObtenerNumeroEntero(busqueda);
                    if (numero != 0)
                    {
                        tareas = tareas.Where(
                        t => (t.ID == Int32.Parse(busqueda))
                    ).AsQueryable();
                    }
                    else
                    {
                        tareas = tareas.Where(
                        t => (t.DESCRIPCION.ToLower()).Contains(busqueda.ToLower())
                        || (t.TIPO_PLANID.DESCRIPCION.ToLower()).Contains(busqueda.ToLower())
                        // || t.ID == Int32.Parse(busqueda)
                        // || (t.UNIDAD.SIGLA.ToLower()).Contains(busqueda.ToLower())
                    ).AsQueryable();
                    }
                }

                if (nivel == 3)
                {
                    var unidad = User.GetClaimValue("Unidad");
                    tareas = tareas.Where(t => (t.UNIDADCODIGO == unidad)).AsQueryable();
                }

                if (planid != 0)
                {
                    tareas = tareas.Where(t => (t.PLANID == planid)).AsQueryable();
                }
                else
                {
                    if (!string.IsNullOrWhiteSpace(unidadCodigo))
                    {
                        var unidad = User.GetClaimValue("Unidad");
                        tareas = tareas.Where(t => (t.UNIDADCODIGO == unidadCodigo)).AsQueryable();
                    }
                }

                if (tipo_plan_id != 0)
                {
                    if (tipo_plan_id == 1)
                        tareas = tareas.Where(t => (t.TIPO_PLANID.TIPO_PLANID == tipo_plan_id)).AsQueryable();
                    else
                        tareas = tareas.Where(t => (t.TIPO_PLANID.TIPO_PLANID != 1)).AsQueryable();
                }
                if (padreid > 0)
                {
                    tareas = tareas.Where(t => (t.PADREID == padreid)).AsQueryable();
                }

                if (tipo_tareaid != 0)
                {
                    tareas = tareas.Where(t => (t.TIPO_TAREAID == tipo_tareaid)).AsQueryable();
                }

                if (!string.IsNullOrWhiteSpace(unidadfiltro))
                {
                    tareas = tareas.Where(t => (t.UNIDADCODIGO == unidadfiltro)).AsQueryable();
                }

                if (tipoPlanSearch != 0)
                {
                    tareas = tareas.Where(t => (t.TIPO_PLANID.TIPO_PLANID == tipoPlanSearch)).AsQueryable();
                }

                if (planesSearch != 0)
                {
                    tareas = tareas.Where(t => (t.PLANID == planesSearch)).AsQueryable();
                }

                if (prioridadSearch != 0)
                {
                    tareas = tareas.Where(t => (t.PRIORIDADID == prioridadSearch)).AsQueryable();
                }
                if (merodisiSearch != 0)
                {
                    tareas = tareas.Where(t => (t.TIPO_DOMINIOID == merodisiSearch)).AsQueryable();
                }
                if (fechaInicio != null)
                {
                    tareas = tareas.Where(t => (t.INICIO == fechaInicio)).AsQueryable();
                }
                if (fechaTermino != null)
                {
                    tareas = tareas.Where(t => (t.PLAZO == fechaTermino)).AsQueryable();
                }

                //Fin de filtros

                //ExportExcel<TareaEstadisticasViewModel>((IEnumerable<TareaEstadisticasViewModel>)tareas);

                var respTotal = tareas.Count();

                //Inicializa variables de paginación
                var pageResult = 10f;
                var pageCount = Math.Ceiling(respTotal / pageResult);

                var respuesta = await tareas
                .Skip((page - 1) * (int)pageResult)//Paginación - salta los resultados de las páginas anteriores a la actuál
                .Take((int)pageResult)//Paginación - selecciona solo la cantidad de registros definidos en la variable pageResult
                .ToListAsync();

                if (respuesta == null || respuesta.Count() == 0)
                {

                    var response = new ResponsePaginationModel
                    {
                        Data = "",
                        CurrentPage = 0,
                        Pages = 1
                    };

                    // resp.Data = ex.Message;
                    resp.statusCode = 404;
                    resp.Message = "No se encontraron resultados";

                    Auditor.registroAuditor(
                    "error", 404, User.GetClaimValue("IP"), int.Parse(User.GetClaimValue("Run")), int.Parse(User.GetClaimValue("Rol")),
                    "Tareas/getTareas/", "No se encontraron resultados", JsonConvert.SerializeObject("page: " + page + ", planid: " + planid + ", tipo_tareaid: " + tipo_tareaid + ", busqueda: " + busqueda), _authContext
                    );

                    return Ok(response);
                    // return NotFound(response);
                    // return resp;
                }
                else
                {
                    var response = new ResponsePaginationModel
                    {
                        Data = respuesta,
                        CurrentPage = page,
                        Pages = (int)pageCount
                    };

                    Auditor.registroAuditor(
                    "get", 200, User.GetClaimValue("IP"), int.Parse(User.GetClaimValue("Run")), int.Parse(User.GetClaimValue("Rol")),
                    "Tareas/getTareas/", "Ok", JsonConvert.SerializeObject("page: " + page + ", planid: " + planid + ", tipo_tareaid: " + tipo_tareaid + ", busqueda: " + busqueda), _authContext
                    );

                    return Ok(response);
                }
            }
            catch (Exception ex)
            {
                Auditor.registroAuditor(
                    "error", 500, User.GetClaimValue("IP"), int.Parse(User.GetClaimValue("Run")), int.Parse(User.GetClaimValue("Rol")),
                    "Tareas/getTareas/", ex.Message, JsonConvert.SerializeObject("page: " + page + ", planid: " + planid + ", tipo_tareaid: " + tipo_tareaid + ", busqueda: " + busqueda), _authContext
                );

                return BadRequest();
            }
        }
