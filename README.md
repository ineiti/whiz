<div align="center">
  <h1>Whiz</h1>
  <p>A copilot for your terminal.</p>
  <p>
    <img src="./whiz.gif" alt="whiz"  style="border-radius: 10px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); padding: 25px;">
  </p>
</div>

## Installation

```bash
npm install -g whiz_cli
```

Now, you will need to set `OPENAI_API_KEY` in your environment. You can do this by adding the following to your `.bashrc` or `.zshrc`. On windows, you can set this in the environment variables.

If you want to use a different model than `gpt-3.5-turbo`, then set `WHIZ_LLM_MODEL` to the model name. You can find a list of models [here](https://platform.openai.com/docs/models). As an example, you can set `WHIZ_LLM_MODEL=gpt-4` to use the `gpt-4` model.

```bash
export OPENAI_API_KEY=<your key>
```

## 🚀 Usage

```bash
# wz <request>
wz curl google and store response in google.html
wz open google.com in chrome
wz list recent github branches sorted by activity
```

## 🤗 Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## 🔖 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
