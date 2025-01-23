# Multilingual Resume Template
![Resume Preview](image.png)

This LaTeX template supports multiple languages (English and German) and allows easy configuration for personal details like name, address, and contact information.

## Features
- Multi-language support: Easily switch between English and German.
- Configurable details: Define personal information in one place.
- Clean and modern design using `IBM Plex Sans`.

## Requirements
1. **Compiler**: Use **LuaLaTeX**.
2. **Font**: Install `IBM Plex Sans` on your system:
   - Download from [IBM Plex GitHub](https://github.com/IBM/plex).
   - Add the font to your system's font library.

## Configuration
Personal details can be set in the configuration section in the `.tex` file:
```latex

ewcommand{\configName}{John Doe}

ewcommand{\configAddress}{Example Street 123}

ewcommand{\configCity}{12345 Sample City}

ewcommand{\configCountry}{Germany}

ewcommand{\configPhone}{+49 123 456 7890}

ewcommand{\configEmail}{example@example.com}

ewcommand{\configDateOfBirth}{01.01.1990 in Sampletown}
```

## Usage
1. Clone the repository.
2. Configure your details in the `.tex` file.
3. Compile with LuaLaTeX:
   ```bash
   lualatex resume.tex
   ```

## License
This project is licensed under the GPL V3 License.
