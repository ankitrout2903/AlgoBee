# Textbase

✨ Textbase is a framework for building chatbots using NLP and ML. ✨

Just implement the `on_message` function in `main.py` and Textbase will take care of the rest :)

Since it is just Python you can use whatever models, libraries, vector databases and APIs you want.

## MY contribution

this is a Ai interview chat bot application coding buddy made whith the help of mercor textbase library has a Inbuilt text editor 

https://www.loom.com/share/9f7a9bcd6ece42fa919b7407caaf3200?sid=fdeb7f14-7f76-4097-9167-e8c24e143efc



## Installation

Clone the repository and install the dependencies using [Poetry](https://python-poetry.org/) (you might have to [install Poetry](https://python-poetry.org/docs/#installation) first).

```bash
git clone https://github.com/cofactoryai/textbase
cd textbase
poetry shell
poetry install
```

start the compiler code
```bash
cd compiler
cd client
npm install
npm run start
cd ../server
npm install
npm start
```

due to my knowledge expertise in javascript and node js so i made the compiler backend api in nodejs as I had less time for hackathon laer the architecture will be improved and will be optimised as this is just a prototype



## Start development server

> If you're using the default template, **remember to set the OpenAI API key** in `main.py`.

Run the following command:

```bash
poetry run python textbase/textbase_cli.py test main.py
```

Now go to [http://localhost:4000](http://localhost:4000) and start chatting with your bot! The bot will automatically reload when you change the code.

_Simpler version using PyPI package and CLI coming soon!_

## Contributions

Contributions are welcome! Please open an issue or a pull request.
