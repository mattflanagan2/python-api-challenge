# python-api-challenge
## Weather API
### Instructions

In this deliverable, you'll create a Python script to visualize the weather of over 500 cities of varying distances from the equator. You'll use the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site., and your problem-solving skills to create a representative model of weather across cities.

### Process
To fulfill the first requirement, I first generated a cities list from the citipy Library.

![Screenshot 2024-03-28 at 11 27 18 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/3fdfefa0-367d-4063-9f90-f299ca9e1cd9)

Next I used the OpenWeatherMap API to retrieve weather data from the cities list I just created. 

![Screenshot 2024-03-28 at 11 28 58 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/93234d11-0314-491c-93f1-d33ee3cf1a38)
![Screenshot 2024-03-28 at 11 29 27 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/60463890-909f-4a44-baa2-1c17bf7d5a81)
![Screenshot 2024-03-28 at 11 29 39 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/bc7cb1b3-d14a-49b8-9ccc-29b80ff05e86)
![Screenshot 2024-03-28 at 11 31 18 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/eb351edf-a7d0-4b7c-8464-c423ef09cad4)

I then created a dataframe out of this data and exported it as a CSV called cities.csv. 
Next I created Scatter plots and compared the Latitude vs. Temperature, Latitude vs. Humidity, Latitude vs. Cloudiness, and Latitude vs. Wind Speed.

![Screenshot 2024-03-28 at 11 36 24 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/74e24897-6eee-4bc8-9851-e56cfabb018d)
![Screenshot 2024-03-28 at 11 37 38 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/1a3e758f-d155-4974-b1d7-050e4336ffb6)
![Screenshot 2024-03-28 at 11 36 44 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/5e9e6108-e2a3-4f51-83b7-a1aa11ad5c45)
![Screenshot 2024-03-28 at 11 37 48 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/d86cd0b4-df80-4773-a0c1-cbc76d9e6861)
![Screenshot 2024-03-28 at 11 36 56 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/c0950bee-a1ab-4d05-9369-1dfe9bfd5a3e)
![Screenshot 2024-03-28 at 11 38 00 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/f6e44f29-5f66-4ab6-ae4e-a4a21c72aff0)
![Screenshot 2024-03-28 at 11 37 06 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/128d3ae5-dbd4-4c1f-b03e-754d6f390a04)
![Screenshot 2024-03-28 at 11 38 17 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/ff514e41-cb53-4d12-9da1-a5ae7064a651)


After that I computed the Linear Regression for each relationship and plotted them.

![Screenshot 2024-03-28 at 11 42 54 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/e6ada65a-97e5-452d-a993-648bd1d81153)
![Screenshot 2024-03-28 at 11 44 17 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/b446095f-3bd1-4958-8661-7d70034b9c7f)
![Screenshot 2024-03-28 at 11 47 09 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/e093bb4f-9494-42ac-8e7d-f7a06d76080c)
![Screenshot 2024-03-28 at 11 44 59 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/e4d9426c-b0e7-4449-86e3-1a340ebc47f2)
![Screenshot 2024-03-28 at 11 47 20 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/b796e0c8-dfc1-4df7-a73a-60745df9f1c1)
![Screenshot 2024-03-28 at 11 45 33 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/978c1b6d-d31f-4ea7-b6cc-01610007c8f5)
![Screenshot 2024-03-28 at 11 47 30 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/72d0e17b-866e-4962-a2d7-29c5d38f476e)
![Screenshot 2024-03-28 at 11 45 59 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/d5fb9377-ed6a-419c-bf08-d89159eaf495)
![Screenshot 2024-03-28 at 11 47 41 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/14f1e285-1bd1-45a9-83b8-43d3f4b43d9d)
![Screenshot 2024-03-28 at 11 46 26 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/15717567-6d77-44bc-b5d6-9a66a69b0242)
![Screenshot 2024-03-28 at 11 48 23 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/c6973df6-582e-4e91-bb31-9d0f1d1483d6)
![Screenshot 2024-03-28 at 11 46 52 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/f092d442-6363-4035-be08-53bd7994006c)
![Screenshot 2024-03-28 at 11 48 34 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/e69308cd-d595-418f-8a54-89568b543684)
![Screenshot 2024-03-28 at 11 52 09 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/0b4f3a6c-0a97-47c0-a0f9-226ade03f417)
![Screenshot 2024-03-28 at 11 52 41 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/e7551045-7ff9-45e6-ae1b-e66cf240207c)
![Screenshot 2024-03-28 at 11 52 25 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/86414f71-a380-40c3-b6d5-5d1960b303ab)
![Screenshot 2024-03-28 at 11 52 53 AM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/e40a8c38-55cf-4981-95b1-e927acf08e2d)


## VacationPy
### Instructions
In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

### Process
I first began with creating a map that displays a point for every city in the city_data_df DataFrame with the size of the point being the humidity in each city.

![Screenshot 2024-03-28 at 12 00 06 PM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/40281237-0a84-4386-9074-658f32a74cbc)


I then created a data frame of my ideal cities based on specific weather parameters.

![Screenshot 2024-03-28 at 12 02 37 PM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/2e77fe85-fd5a-4013-9792-e84e3375cd0c)
![Screenshot 2024-03-28 at 12 02 51 PM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/4ae6fe3b-2c17-432e-a855-2575e975aabf)


Next I got a list of hotels in my ideal cities

![Screenshot 2024-03-28 at 12 04 01 PM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/2c2fb094-ca9c-4b02-837f-9ec1540ab31e)
![Screenshot 2024-03-28 at 12 05 01 PM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/d5932c0d-ad2c-4876-9702-a9ebee6ce1d4)
![Screenshot 2024-03-28 at 12 05 37 PM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/986a6ded-90dd-4e62-ad86-844b282b3c45)
![Screenshot 2024-03-28 at 12 09 47 PM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/dc33cd52-f0b1-4b56-b9bb-562c3d858304)


Finally I added this data to the map. I also created it the map so that when you hover over each country the hotel name and the city along with other information pops up. 

![Screenshot 2024-03-28 at 12 08 08 PM](https://github.com/mattflanagan2/python-api-challenge/assets/146908072/d181f7e5-ec2a-475a-a8cd-47eea3d9eaf6)






