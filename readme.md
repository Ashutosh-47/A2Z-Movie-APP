<!-- 1. TMDB ( The Movie Database ) API ( Application program interface ) data store someWhere else we can get/Post that Data and use it

2. To Get Movies use get movies( url ) ;  fetch Api return.json() to convert  it into a JavaScript data structure form so that it can be in a readable form beacuse we receive in a String Format.

3. To Show Movies use  showMovies( url ) ;  pass data Api --> objects then data.result Array of Objects
4. create div for movies and append it into Main class.
5. To give different colour to votes pass function which return string which used as class getcolor(vote);



// ----------------------------- Stuck here when showing movie image -------------------------------------------------------

I was putting simply name poster_path but it is the path so I go and search in API docs and found the url to show images.


//--------------------------------------------------- Search ------------------------------------------------------------------
1. Simply pass value init and call getMovie(url) according to value that pass in sear value ; Seperate url also for Search like image


//------------------------------------------------------ genere ----------------------------
1.  In Api url  and just add [ Base url + /genre/movie/list + API key] we get This Data and Paste it----> format online  Json Format
2. setGenre() ;  use loop on genre [] and add it in to tag div
3. On Genre[] call for loop and create div of each ( Action / Family ) add EventListner so when click selectGenre[] that id push in it and fetch acc to it  and click same immediately that effect will remove and highLight() --> create clear() ; 
4. add EvenListner if prev > 0 ( on prev div ) & next <= total ( on next div ) run pageCall () ;


//------------------------------------------------------------- YouTube Link ---------------------------------------------------------------
1. Create Know More button in OverView
2. showMovie() KnowMore Listner on that id we click
3. overlay come and display video ( overLay div hidden when click it show)
4. Simlar to getMovie() just Slightly changes fetch data for changed Api toget videos and run loop
5. Create Emb[] and add iframe { copy api of video and put on google then youtube link click embded and copy iframe code}
6. emb[] store all heml iframe and the appen in div that will create and dots represent arr[] of numbers 1 ,2,3, { idx +1 as 0 based index}
7. Var ActiveSlide means curr slide display and it changes ++ / -- when we click on left or right arrow and add class show or hide acc to that to display curr videp


// 1. See top movies List with search option 
//2. with Genre Filters with two or more Genres and clear option ( In discover Movies in API docs i see Genre option so I thought to add it)
// 3. Pagination option(Next/Previous Page) -->
