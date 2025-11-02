End-to-End Iris ML API (Colab)

Files included:

- End_to_End_Iris_API.ipynb : Google Colab notebook (train + Flask API via ngrok)

- sample_output.png : Example API request/response screenshot


How to use:

1. Upload the notebook to Google Colab and open it.

2. Run the first cell to install dependencies.
3. Run the training cell to create iris_model.pkl.
4. Run the Flask API cell. Copy the ngrok URL printed in output.
5. Test using requests.post(<ngrok-url>/predict, json={'features':[...]}).
