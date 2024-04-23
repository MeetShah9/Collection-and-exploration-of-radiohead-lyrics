# Collection and Exploration of Radiohead lyrics
## Overview
This data was collected with intentions of training a RNN to gnereate lyrics similiar in nature, but due to limited quantity of data being avaiable the model was generating garbage.
Maybe I will come back to this problem again in future but for now i'm leaving this problem.

# 1) Data Collection

This Python script scrapes the lyrics of albums by the band Radiohead from Genius.com using their API. It saves the lyrics of each album to individual JSON files.

# 2) Data Cleaning 
This script includes several text preprocessing functions implemented in Python for cleaning up text data.
This uses Regex Libaray to clean data. 

# 3) EDA
## This script performs basic EDA on the collected data.
### It uses a word cloud to show which words are most frequently used by Radiohead in their songs.
<img width="1146" alt="Screenshot 2024-04-23 at 11 15 51 AM" src="https://github.com/MeetShah9/Collection-and-exploration-of-radiohead-lyrics/assets/148629466/53330940-5c97-4dfe-a7ea-5ae655822f7e">

### It also uses a bar graph to show average number of words used per song in each album.
<img width="1127" alt="Screenshot 2024-04-23 at 11 17 01 AM" src="https://github.com/MeetShah9/Collection-and-exploration-of-radiohead-lyrics/assets/148629466/a96ec2b3-82d8-487b-9985-3a7807e28bc3">



## Cloning the Repository

To clone and run this project locally, use the following commands:

```bash
git clone https://github.com/MeetShah9/Collection-and-exploration-of-radiohead-lyrics.git
```

To install the required Python libraries, run the following command in your terminal:

```bash
pip install -r requirements.txt
```





## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Genius API](https://docs.genius.com/)
- [LyricsGenius](https://github.com/johnwmillr/LyricsGenius)

## Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request.
