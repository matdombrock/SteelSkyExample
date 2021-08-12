<steelsky>
{
  "title":"Site Directory",
  "description":"A list of all assets on this website."
}
</steelsky>
# Site Directory

Directory listings are auto-generated when you run SteelSky. The listing will be put in a `listing.json` file at the root of your output directory. This file can be accessed and used to generate indepth listings and extract customizable page meta-data. 

---

<select id="filter" onchange="ssList.updateFilter()">
  <option value=".html">HTML</option> 
  <option value="all">All</option>
  <option value=".gif">GIF</option>
  <option value=".png">PNG</option>
  <option value=".jpg">JPG</option>
  <option value=".txt">TXT</option>
</select>
<input type="text" id="search" onchange="ssList.updateFilter()" placeholder="search term">

<div id="listing-area"></div>

<style>
.ss-listing-item-wrap{
  padding:0.75rem;
  margin:0.25rem;
}
.ss-listing-item-title{
  font-size:2rem;
}
.ss-listing-item-title a{
  text-decoration:none;
}
</style>

<script src="/ssList.js"></script>