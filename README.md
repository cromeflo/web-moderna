# La Web Moderna
## Autor

- **Alumno:** Carlos Enrique Romero Flores  
- **Curso:** Code 201  
- **Correo electrónico:** cromeflo@gmail.com  
- **Fecha Proyecto:** 2024-11-20

## Sobre el Proyecto

**"La Web Moderna"** es un recurso diseñado para explorar los fundamentos y avances clave en el desarrollo de aplicaciones web. Abarca temas esenciales como HTML, CSS, JavaScript, frameworks modernos, diseño responsivo, optimización para motores de búsqueda (SEO) y mejores prácticas en desarrollo front-end y back-end. Este proyecto busca ser una guía práctica y conceptual para desarrolladores de todos los niveles que deseen crear experiencias web atractivas, funcionales y escalables.

# Explicación del Código eslintrc JSON

```json
{
    "env": {
        "browser": true,
        "es2021": true
    },
    "extends": ["eslint:recommended"],
    "parserOptions": {
        "ecmaVersion": "latest",
        "sourceType": "module"
    },
    "rules": {
        "indent": ["error", 2],
        "linebreak-style": ["error", "unix"],
        "quotes": ["error", "single"],
        "semi": ["error", "always"],
        "no-unused-vars": "warn",
        "no-console": "warn"
    }
}  
```

"env": {...}
Define el entorno en el que se ejecutará el código.

"browser": true: Especifica que el entorno es un navegador (habilita variables globales como window y document).
"es2021": true: Habilita características de ES2021 (por ejemplo, Promise.allSettled).
"extends": ["eslint:recommended"]
Incluye las reglas recomendadas de ESLint como base para la configuración.

"parserOptions": {...}
Configura opciones para el análisis del código.

"ecmaVersion": "latest": Permite usar la versión más reciente de ECMAScript.
"sourceType": "module": Indica que el código está organizado en módulos (permite usar import y export).
"rules": {...}
Define reglas específicas para ESLint.

"indent": ["error", 2]: Exige una indentación de 2 espacios. Marca un error si no se cumple.
"linebreak-style": ["error", "unix"]: Obliga a usar saltos de línea estilo Unix (\n).
"quotes": ["error", "single"]: Obliga a usar comillas simples para cadenas de texto.
"semi": ["error", "always"]: Obliga a usar punto y coma al final de cada instrucción.
"no-unused-vars": "warn": Advierte sobre variables declaradas que no se usan.
"no-console": "warn": Advierte sobre el uso de console.log u otras funciones de consola.