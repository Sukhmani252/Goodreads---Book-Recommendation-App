## Goodreads: Book Recommendation App

### Project Overview:

This project aims to design an interactive tool using Goodreads data that helps users build their ideal reading list by recommending books based on each user’s unique preferences—from timeless classics to undiscovered hidden gems—and to bring each book to life through real review insights.

### Data Structure:

The dataset includes 1M+ reviews from 13K+ books on goodreads.com. There are two core tables: the works table, which includes book metadata such as title, author, publication year, genres, and average rating; and the reviews table, which includes user-written reviews and reader engagement stats.


I created some additional supporting tables to help users explore genres, rating distribution, and related books more effectively. 

***work_genre:*** Contains work_id and genre, linking each book to its associated genres.

***ratings:*** Contains work_id, rating_category, and ratings_count

***genres:*** A separate reference table that stores the complete list of unique genres.

***similar_books:*** Contains work_id and similar_book, mapping books to related titles.

