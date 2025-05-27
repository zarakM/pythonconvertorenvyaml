# 🔄 Python Env/YAML Converter

A simple Python tool that helps convert `.env` files to `.yaml` and vice versa. Perfect for DevOps engineers and developers who work across multiple environments and need fast, reliable config format switching.

## 🚀 Features

✅ Convert all files in baseEnv to .yaml files in convYaml directory.

✅ Convert all files in baseYaml to .yaml files in convEnv directory.

✅ CLI interface for quick integration into pipelines

## 📦 Installation

```bash
git clone https://github.com/zarakM/pythonconvertorenvyaml.git
cd pythonconvertorenvyaml
```

## 🛠 Usage

### Convert `.env` to `.yaml`

```bash
python main.py --env-to-yaml input.env output.yaml
```

### Convert `.yaml` to `.env`

```bash
python main.py --yaml-to-env input.yaml output.env
```

> Make sure to replace `main.py` with the actual filename if it's different.

## 🌍 Why This Tool?

Working with environments where developers are commiting in env format. This tool ensures smooth, consistent conversions to support better automation and fewer errors in deployment.

## 🤝 Contributing

Pull requests and issues are welcome! Feel free to suggest features, report bugs, or fork and build on the project.

## 📄 License

This project is licensed under the MIT License.
```

Let me know if you'd like badges (like for license, stars, forks, etc.) or instructions for packaging as a CLI tool.
