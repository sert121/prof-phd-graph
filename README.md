# prof-phd-graph
## Intro
A twitter-based social graph that allows one to visualize relationships between professors and phD students.  
The phD students and professors are selected from an active community of researchers within the machine learning community, and can be generalized to any other community. We use ```TwitterAPI```, ```snsscrape```, and ```Google Scholar``` to acquire relevant metadata for each user.
Each node represents a user, and an edge symbolises interaction (on the basis of quote-tweets/replies) between two users.    
 
## Usage
The graph is deployed at [].   
For development, feel free to fork/star this repository.   
To develop this locally, execute the following steps:     
```python
pip install -r requirements
streamlit run stream.py
```

## License
```MIT License```
