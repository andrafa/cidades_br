# Cidades Brasileiras

O arquivo `cidades.json` contém uma lista das cidades do Brasil com os campos estado, cidade, latitude, longitude e um boolean que identifica se a cidade é uma capital ou não.

Os dados foram obtidos da pagina wiki.openstreetmap.org:

[https://wiki.openstreetmap.org/wiki/WikiProject_Brazil/Lista_Completa_de_Cidades](https://wiki.openstreetmap.org/wiki/WikiProject_Brazil/Lista_Completa_de_Cidades)

## Modelo
```
[
	{
		"estado": "UF",
		"cidade": "Cidade",
		"lat": -9.999999,
		"long": -99.999999,
		"capital": false
	}
]
```
