# si649robogames
public files for the robogames

The server directory has the server implementation

The client directory has example clients and a web interface to modify the guesses during a running game

To run the server

```
cd ./server
python ./api.py -d ./example1/ -s -t1s bob examplematch1
```  
To run dashboard
```
cd ./clients/
streamlit run dashboard.py
```
