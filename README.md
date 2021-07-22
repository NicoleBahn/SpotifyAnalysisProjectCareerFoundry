# SpotifyAnalysisProjectCareerFoundry
Spotify Data from 2017 to 2020

The Data source:
  Spotify- https://www.kaggle.com/pepepython/spotify-huge-database-daily-charts-over-3-years
 
 Global Shapefile - https://tapiquen-sig.jimdofree.com/english-version/free-downloads/world/
  

The source is from the company Spotify that is automated. This is internal data that the company shares freely. The company is a third party that shares music from around the world, however, there could be biases from the company as if it gains revenue from ranking music. (*side note*The creators of the data set made a popularity scale due to the bias nature of spotify’s ranking. )

Overview of the data:
-Title: Name of a song

-URI: Unique identifier of a song created by Spotify

-Country Global and 34 countries where Spotify operates, namely Argentina, Australia, Austria, Belgium, Brazil, Canada, Chile, Colombia, Costa Rica, Denmark, Ecuador, Finland, France, Germany, Great Britain, Indonesia, Ireland, Italy, Mexico,Malaysia, Netherlands, New Zealand, Norway, Peru, Philippines, Poland, Portugal, Singapore, Spain, Sweden, Switzerland, Taiwan, Turkey, USA

-Popularity_ The popularity score calculated taking into account both the number of days a song stayed in the Top200 and the position it stayed in every day, weighting more the top positions

-Artist: Name of the songs' artist

-Album/Single: Whether the song was published as a single or as part of an album or compilation

-Genre: The predominant genre of an artist according to Spotify’s classification

-Artistfollowers: The number of followers the artist has on Spotify on the 5th of November 2020 -Explicit: Whether the song is rated as ‘Parental Advisory Explicit Content’ or not 

-Album: Name of the album the song belongs to -Releasedate: Date on which the song was published

-Track_number: The position of the song on its respective album

-Track _album: Total songs present in the album

-Danceability: How suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable

-Energy: It is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy. Perceptual features contributing to this attribute include dynamic range, perceived loudness, timbre, onset rate, and general entropy

-Key: The estimated overall key of the track. Integers map to pitches using standard Pitch Class notation. E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on. If no key was detected, the value is -1

-Loudness: The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks. Loudness is the quality of a sound that is the primary psychological correlate of physical strength (amplitude). Values typical range between -60 and 0 db

-Mode Mode: indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0

-Speechiness: Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks

-Acousticness: A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic

-Instrumentalness: Predicts whether a track contains no vocals. “Ooh” and “aah” sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly “vocal”. The closer the instrumentalness: value is to 1.0, the greater likelihood the track contains no vocal content. Values above 0.5 are intended to represent instrumental tracks, but confidence is higher as the value approaches 1.0

-Liveness: Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live

-Valence: A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry)

-Tempo: The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration

-Durationms: The duration of the track in milliseconds -Timesignature: An estimated overall time signature of a track. The time signature (meter) is a notational convention to specify how many beats are in each bar (or measure)

-Genrenew: The predominant genre of an artist according to our reclassification of Spotify’s 1200 genres -Dayssincerelease: Number of days passe from the release of the track -Releasedafter2017: Dummy equal to 1 if the track was released after 2017 -Syuzhetnorm: Tone of the lyrics based on the library Syuzhet. The initial result is normalized on the scale: -1 (negative), 0 (neutral), 1 (positive).

-Angernorm2: Number of words related to anger divided by the total number of words found by the dictionary -Anticipationnorm2: Number of words related to anticipation divided by the total number of words found by the dictionary

-Disgustnorm2: Number of words related to fear divided by the total number of words found by the dictionary -Fearnorm2: Number of words related to fear divided by the total number of words found by the dictionary

-Joynorm2: Number of words related to joy divided by the total number of words found by the dictionary -Sadnessnorm2: Number of words related to sadness divided by the total number of words found by the dictionary

-Surprisenorm2: Number of words related to surprise divided by the total number of words found by the dictionary -Trustnorm2: Number of words related to trust divided by the total number of words found by the dictionary

-Bayes: Tone of the lyrics according to Bayes on the scale: -1 (negative), 0 (neutral), 1 (positive)

-LDATopic: Topic of the lyrics according to the categories: Love, Thug, Nostalgia, Explore, Fun, Desire, Hope and Celebrate -Popumax: The top position reached by a track in the 1401 days we have data for

-Top50_dummy: A dummy equal to 1 if the top position reached by a song is 50 or higher


Cleaning procedures entailed ensuring there was no missing data, duplicates, & consistency checks.


  Define questions to explore: 
•	Do countries share same top ranking artists or songs?

•	Is there a correlation between popularity of an artist and being in the top 50 charts?

•	Are there different genres that are most popular per country?

Visualization of data and results on Tableau: https://public.tableau.com/app/profile/nicole7538/viz/SpotifyFinalProject_16268316599600/GlobalMusicPopularity?publish=yes
