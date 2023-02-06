# <p align="center"> <ins>SQLalchemy-challenge</ins>

## <ins>Background</ins>

After working hard, I have decided to treat myself to a long holiday vacation in Honolulu, Hawaii. To help with my trip planning, I decided to do a climate analysis about the area. The following sections outline the steps that I took to accomplish this task.

## <ins>Part 1: Analyze and Explore the Climate Data</ins>
In this section, I used Python and SQLAlchemy to do a basic climate analysis and data exploration of my climate database. Specifically, I used SQLAlchemy ORM queries, Pandas, and Matplotlib. To do so, I completed the following steps:

1. I used `climate_starter.ipynb` and `hawaii.sqlite` files to complete my climate analysis and data exploration.

2. Next, I used the SQLAlchemy `create_engine()` function to connect to my SQLite database.

3. After, I used the SQLAlchemy `automap_base()` function to reflect my tables into classes, and then saved references to the classes named station and measurement.

4. Finally, I linked Python to the database by creating a SQLAlchemy session.

5. Once this was all completed, I performed a precipitation analysis and then a station analysis by completing the steps in the following two subsections.
