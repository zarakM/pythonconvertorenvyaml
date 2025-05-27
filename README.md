🔄 Python Env/YAML Converter
A simple and efficient Python tool to convert between .env and .yaml configuration files. Ideal for developers and DevOps engineers working across different deployment environments.

🚀 Features
✅ Convert all files in baseEnv to .yaml files in convYaml directory.

✅ Convert all files in baseYaml to .yaml files in convEnv directory.

✅ CLI interface for quick integration into pipelines

📦 Installation
bash
Copy
Edit
git clone https://github.com/zarakM/pythonconvertorenvyaml.git
cd pythonconvertorenvyaml
🛠 Usage
Convert .env to .yaml
bash
Copy
Edit
python main.py --env-to-yaml path/to/input.env path/to/output.yaml
Convert .yaml to .env
bash
Copy
Edit
python main.py --yaml-to-env path/to/input.yaml path/to/output.env
Replace main.py with your actual script name if different.

🌍 Why Use This?
Managing environment configs in different formats can be a hassle—especially when shifting between local dev, CI/CD, and cloud. This tool keeps things consistent and automated.

🤝 Contributing
Pull requests are welcome! If you have suggestions or find a bug, feel free to open an issue.

📄 License
This project is licensed under the MIT License.

