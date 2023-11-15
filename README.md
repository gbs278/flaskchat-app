# FlaskChat App

This is a simple chat application built with Flask-SocketIO and a PostgreSQL database. Users can join different chat rooms and send messages to other users in real-time.

## Usage

To run the app locally, follow these steps:

1. Clone this repository
2. Create a virtual environment: `virtualenv venv`
3. Activate the virtual environment: `source venv/bin/activate`
4. Install the required dependencies: `pip install -r requirements.txt`
5. Run the app: `python app.py`

## Deployment

This app is currently deployed on Heroku. To deploy the app on Heroku, follow these steps:

1. Create a new Heroku app
2. Set up a PostgreSQL database and add its URL as an environment variable on Heroku
3. Add a new Git remote: `heroku git:remote -a <your-heroku-app-name>`
4. Push the code to Heroku: `git push heroku master`
5. Open the app: `heroku open`

## Contributing

Contributions are welcome! If you find any bugs or issues with the app, feel free to open a new issue or submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
