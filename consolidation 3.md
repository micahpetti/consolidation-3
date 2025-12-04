Consolidation 3

For consolidation 3 I chose to recreate an activity from week 3. It was the week where I felt like a had the most grasp on the tak and was able to complete it. I remade the sitemap of the graveyard I chose in the Geojson. This time I approaced it slightly differently. 

Originally when I made the map, I plotted and named the graves and left it at that. Upon further consideration I realised that my choide to do that was not very intentional, nor functional. Presuming that the map would be a piece of public access archaeology, a map that arbitrarily numbers graves would not be very informativd to anyone without also having the spreadsheet of data that I collected. 

The second time aorund I chose to add more information that I collected to the gravestone icons. I chose the dimensions of the stones because that was most accessible to me at the time of reattempting the activity, but I can imagine that a variety of different data points would also be useful to include. I think this time engaging with the activity I tried to engae with the idea that this map could be a learning tool involved in public archaeology. For me, that meant considering the accessibility of the information aswell as maintaining respect for the real individuals we engage with when archaeology deals with death. In module three the readings discussed humanizing the record at length. I think I fell short of this goal with my additions to the map. That being said, I think in order to do that it would involve a much longer more comprehensive study of the history and lives of those remembered by the graves. My data that I collected initially fell short of that goal. THough, I do wonder what that process would look like. Possibly speaking with the family of the individuals or looking into any records that might exist of their lives. Ive attached the new code for the map at the bottom of the document 

In this mudule I tried google collab and it worked out much better for me than jupyter lab! I attempted the activity for week 11 with R on collab after the feedback for week 11 showed me how to switch collab to R. It was interesting to explore the open data and the podcast episode for week 11 was enlightening for me to hear about the thinking behind open access research. I had never considered the process behind storing and archiving research in a way that is constructive. Replication is a critical part of digital archaeology because digital contests allow us to contantly reinterpret and improve data and its connections between other pieces of research. 

I think for this module I deserve a B. I fell short on submitting my work for the weeks on time but I learned alot through the readings and I liked interacting with my classmates through hypothesis. I also consider it a big win for myself to have discovered that using collab works much better for me! 

 "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {},
      "geometry": {
        "coordinates": [
          [
            [
              -75.639990673718,
              45.34887993484699
            ],
            [
              -75.63953035777259,
              45.34806508670201
            ],
            [
              -75.63864433610333,
              45.34840075691096
            ],
            [
              -75.63913926227033,
              45.34921560022369
            ],
            [
              -75.639990673718,
              45.34887993484699
            ]
          ]
        ],
        "type": "Polygon"
      },
      "id": 0
    },
    {
      "type": "Feature",
      "properties": {
        "1": "stbc",
        "marker-color": "#7e7e7e",
        "marker-size": "medium",
        "marker-symbol": "circle",
        "year": 1944,
        "height mm": 750,
        "width mm": 460,
        "thickness mm": 160,
        "height of base mm": 220,
        "width of base mm": 610
      },
      "geometry": {
        "coordinates": [
          -75.63948426081785,
          45.34896896890908
        ],
        "type": "Point"
      },
      "id": 1
    },
    {
      "type": "Feature",
      "properties": {
        "2": "stbc",
        "year": 1943,
        "height mm": 950,
        "width mm": 860,
        "thickness mm": 190,
        "height of base mm": 310,
        "width of base mm": 1000
      },
      "geometry": {
        "coordinates": [
          -75.63947143428089,
          45.348961743447944
        ],
        "type": "Point"
      },
      "id": 2
    },
    {
      "type": "Feature",
      "properties": {
        "3": "stbc",
        "year ": "nd",
        "Height mm": 640,
        "Width mm": 340,
        "Thickness mm": 55,
        "Height of base": 70,
        "Width of base": 180
      },
      "geometry": {
        "coordinates": [
          -75.63945652537329,
          45.34895457370459
        ],
        "type": "Point"
      },
      "id": 3
    },
    {
      "type": "Feature",
      "properties": {
        "4": "stbc",
        "year": 1923,
        "Height mm": 662,
        "width mm": 360,
        "thickness": 35
      },
      "geometry": {
        "coordinates": [
          -75.63944467948599,
          45.34894791359491
        ],
        "type": "Point"
      },
      "id": 4
    },
    {
      "type": "Feature",
      "properties": {
        "5": "stbc",
        "year": 1909,
        "height mm": 2340,
        "width mm": 410,
        "thickness mm": 410,
        "base height mm": 580,
        "base width mm": 740
      },
      "geometry": {
        "coordinates": [
          -75.63945020756663,
          45.348922938174866
        ],
        "type": "Point"
      },
      "id": 5
    }
  ]