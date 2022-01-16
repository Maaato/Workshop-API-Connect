# [[Módulo 5] Ejercicio 1: SOAP](https://www.ibm.com/docs/en/api-connect/5.0.x?topic=endpoint-tutorial-creating-invoke-rest-api-definition)

## Objetivos

```
> Consumir WebService: http://www.dneonline.com/calculator.asmx?WSDL
> Validación y Control de errores.
> Manjear una respuesta en formato JSON.
```

## Requerimientos

☐ Consumir URL Backend : http://www.dneonline.com/calculator.asmx?WSDL <br/>
☐ Usar Propiedades de URL <br/>
☐ Usar ClientId API Key [ X-IBM-Client-Id ] <br/>
☐ Usar ClientSecret API Key [ X-IBM-Client-Secret ] <br/>
☐ URL de exposicion: <br/>
- operation : GET
- basepath: /workshop/exe3
- path: /sumar
- path: /restar
- path: /multiplicar
- path: /dividir
- REQ : {"numA":X,"numB":Y}
- RES : {"result":Z}

## Resultado Esperados

<div align="center"><img src="./imgs/68747470733a2f2f6a656c7669782e636f6d2f77702d636f6e74656e742f75706c6f6164732f323032302f30392f2544312538316c69656e742d7365727665722e6a706d.png" align="center" width="50%"/><img src="./imgs/68747470733a2f2f6a656c7669782e636f6d2f77702d636f6e74656e742f75706c6f6164732f323032302f30392f2544312538316c69656e742d7365727665722e6a706e.png" align="center" width="50%"/></div> 
<div align="center"><img src="./imgs/68747470733a2f2f6a656c7669782e636f6d2f77702d636f6e74656e742f75706c6f6164732f323032302f30392f2544312538316c69656e742d7365727665722e6a706f.png" align="center" width="50%"/><img src="./imgs/68747470733a2f2f6a656c7669782e636f6d2f77702d636f6e74656e742f75706c6f6164732f323032302f30392f2544312538316c69656e742d7365727665722e6a706g.png" align="center" width="50%"/></div> 
<div align="center"><img src="./imgs/68747470733a2f2f6a656c7669782e636f6d2f77702d636f6e74656e742f75706c6f6164732f323032302f30392f2544312538316c69656e742d7365727665722e6a706h.png" align="center"/></div>

## Referencias ⚙️
- [Calcultator WSDL](http://www.dneonline.com/calculator.asmx?WSDL)
- [Create, deploy and test a new API using the API Connect Developer Toolkit](https://ibm.github.io/cloudpakforintegration-workshop/exercise-api-connect/)
- [Creating Invoke REST API](https://www.ibm.com/docs/en/api-connect/5.0.x?topic=endpoint-tutorial-creating-invoke-rest-api-definition)
