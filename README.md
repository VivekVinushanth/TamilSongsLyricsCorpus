# TamilSongsLyricsCorpus
A corpus of lyrics of Tamil Movie Songs. Original data was scraped from the [website](https://www.tamilpaa.com/)

## Directory Structure
-----

"├── Raw_Data : The data scraped dirctly from website"
  "├── Tamil_movie_song_lyrics_2017 - Folder with individual JSON for lyrics from Tamil Movies of 2017"
  "├── Tamil_movie_song_lyrics_2018 - Folder with individual JSON for lyrics from Tamil Movies of 2018"
  "├── Tamil_movie_song_lyrics_2019 - Folder with individual JSON for lyrics from Tamil Movies of 2019"
  "├── Tamil_movie_song_lyrics_2020 - Folder with individual JSON for lyrics from Tamil Movies of 2020"
  ├── Tamil_movie_song_lyrics_random_2300+ - Folder with individual JSON for lyrics from Tamil Movies
  ├── Tamil_movie_song_lyrics_2017 - JSON File incorporated lyrics from Tamil Movies of 2017
  ├── Tamil_movie_song_lyrics_2018 - JSON File incorporated lyrics from Tamil Movies of 2018
  ├── Tamil_movie_song_lyrics_2019 - JSON File incorporated lyrics from Tamil Movies of 2019
  ├── Tamil_movie_song_lyrics_2020 - JSON File incorporated lyrics from Tamil Movies of 2020
  ├── Tamil_movie_song_lyrics_random_2300+.json - JSON File incorporated lyrics from Tamil Movies
  
├── PreProcessedData : The data preprocessed for field-values(E.g. A.R.Rahman => A. R. ரஹ்மான்) in English
  ├── Tamil_Songs_Lyric_2017 - Folder with individual preprocessed JSON for lyrics from Tamil Movies of 2017
  ├── Tamil_Songs_Lyric_2018 - Folder with individual preprocessed JSON for lyrics from Tamil Movies of 2018
  ├── Tamil_Songs_Lyric_2019 - Folder with individual preprocessed JSON for lyrics from Tamil Movies of 2019
  ├── lyrics_tamil_movies_songs_2017 - Preprocessed JSON File incorporated lyrics from Tamil Movies of 2017
  ├── lyrics_tamil_movies_songs_2018 - Preprocessed JSON File incorporated lyrics from Tamil Movies of 2018
  ├── lyrics_tamil_movies_songs_2019 - Preprocessed JSON File incorporated lyrics from Tamil Movies of 2019
  
├── ModifiedData : The data modified with adding more fields ("வகை","நுகர்ச்சி","மதிப்பீடு")  
  ├── lyrics_2017 - Modified JSON File incorporated lyrics from Tamil Movies of 2017
  ├── lyrics_2018 - Modified JSON File incorporated lyrics from Tamil Movies of 2018
  ├── lyrics_2019 - Modified JSON File incorporated lyrics from Tamil Movies of 2019
  

JSON Structure
---
Every RAW and Pre-Processed data JSON file has fields of 
1. "திரைப்படம்" - Movie
2. "பாடலாசிரியர்" - Lyricist  
3. "இசையமைப்பாளர்" - Music Director
4. "பாடல்" - Song
5. "வருடம்" - Year releases
6. "பாடியவர்கள்" - Singers/Artists
7. "பாடல்வரிகள்" - Lyrics 

Every Modified data JSON file has fields of 
1. "திரைப்படம்" - Movie
2. "பாடலாசிரியர்" - Lyricist  
3. "இசையமைப்பாளர்" - Music Director
4. "பாடல்" - Song
5. "வருடம்" - Year releases
6. "பாடியவர்கள்" - Singers/Artists
7. "பாடல்வரிகள்" - Lyrics 
8. "வகை" - Genre
9. "நுகர்ச்சி" - Views
10."மதிப்பீடு" - Rating

TO-DO
---
* PreProcess and Modify Data for 2020
* PreProcess and Modify Data for mixed collection 

