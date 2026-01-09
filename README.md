# Game Campaign Generator Prompts

Este repositorio contiene prompts YAML diseñados para la generación de campañas, personajes y escenarios para juegos de mesa usando modelos de lenguaje (LLMs) integrados con GitHub Models.

## Estructura

- `prompts/`: Prompts principales en formato `.prompt.yml`
- `examples/`: Resultados de ejemplo
- `tests/`: Pruebas para validar prompts
- `docs/`: Documentación adicional

## Uso

Modifica los prompts en la carpeta `prompts` y usa la pestaña GitHub Models para ejecutar, versionar y evaluar tus prompts con diferentes modelos LLM.

## Licencia

MIT License.

```sh
game-campaign-generator-prompts/
│
├── README.md                  # Descripción del proyecto, uso y ejemplos
├── .gitignore                 # Para ignorar archivos innecesarios
├── LICENSE                   # Licencia del proyecto
│
├── models/                   # Si hay modelos propios o scripts de configuración
│
├── prompts/                  # Archivos .prompt.yml para distintos propósitos
│   ├── campaign-generator.prompt.yml   # Prompt principal para generación de campañas
│   ├── character-generator.prompt.yml  # Prompts adicionales para personajes
│   └── scenario-generator.prompt.yml   # Prompts para escenarios
│
├── examples/                 # Ejemplos de uso o resultados generados
│   └── campaign-sample.txt
│
├── tests/                    # Pruebas para validar prompts y su output
│   └── test_campaign.yml
│
└── docs/                     # Documentación adicional y guías de integración
    └── usage.md
```
