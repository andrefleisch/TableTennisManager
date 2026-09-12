# Table Tennis Manager

Table Tennis Manager is a small desktop application for organizing player rotation during table tennis sessions. It keeps the waiting queue, score, and match history in one place so players do not have to manage them manually.

> This was a collaborative university project developed at the Pontifical Catholic University of Paraná (PUCPR) in 2024 for the Algorithmic Reasoning course in the Software Engineering program.

## Features

- Starts matches with two players and a target score of 5, 7, or 11 points.
- Adds and removes players from a waiting queue.
- Records each match result and rotates the losing player back into the queue.
- Displays, clears, and saves match history locally in `historico.json`.

The application interface and supporting documentation are in Portuguese.

## Technologies

- Python
- Tkinter and CustomTkinter
- JSON for local history persistence

## Run locally

Python 3 with Tkinter support is required.

```bash
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install -r requirements.txt
python3 main.py
```

On Windows, activate the environment with `.venv\Scripts\activate`.

## Documentation

See the illustrated [usage manual](./Manual%20de%20Utiliza%C3%A7%C3%A3o.pdf) for the application flow and interface.

## License

This project is available under the [MIT License](./LICENSE).
