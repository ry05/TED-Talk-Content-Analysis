# TED Talk Transcript Corpus

This repository consists of data on 4000+ TED talks which have been scraped from the [official TED website]() during 4th April, 2021 and 7th April, 2021. All code used for scraping is located on this [deepnote article](https://deepnote.com/@ramshankar-yadhunath/Scraping-TED-fRqC4ebhTRaNrtcOSrIXMQ).

## Attributes of data

### Talk Attributes

Filename: `talk_data.csv`

1. talk_descr: Description of the talk
2. event: Name of the TED event where the talk was presented
3. talk_name: Name of the talk
4. duration: Time duration of the talk in seconds  
5. tags: TED-authorised tags for the talk
6. recorded_at: Date when the talk was recorded
7. published on: Date when the talk was published

### Speaker Attributes

Filename: `speaker_data.csv`

1. talk: Name of the talk
2. speaker: Name of the speaker
3. speaker_title: Title of the speaker (Example: Miss, Mr)
4. speaker_occ: Occupation of the speaker
5. speaker_bio: Short bio or intro about the speaker

### Talk Transcripts (The corpus)

Filename: `transcript_data.csv`

1. title: Name of the talk
2. transcript: Transcript of the talk

