---
title: "USGS 3DEP Standard DEMs now available via OpenTopography"
url: "https://opentopography.org/news/USGS-3DEP-DEMs-now-available"
date: "Wed, 16 Jun 2021 22:01:19 +0000"
author: "beckley"
feed_url: "https://opentopography.org/rss.xml"
---
<div class="field field-name-field-news-posting-date field-type-datestamp field-label-hidden"><div class="field-items"><div class="field-item even"><span class="date-display-single">Sep 2, 2021</span></div></div></div><div class="field field-name-body field-type-text-with-summary field-label-hidden"><div class="field-items"><div class="field-item even"><p><img alt="USGS LOGO" src="https://cloud.sdsc.edu/v1/AUTH_opentopography/www/images/logos/ARRA10_USGS_logo.png" style="float: right; height: 124px; width: 334px;" />OpenTopography is pleased to announce that we're now offering access to <a href="https://www.usgs.gov/core-science-systems/ngp/3dep/about-3dep-products-services?qt-science_support_page_related_con=0#qt-science_support_page_related_con" target="_blank">USGS 3D Elevation Program (3DEP) Standard Digital Elevation Models (DEMs)</a> through our easy to use web-based interface with associated processing and visualization tools. USGS 3DEP DEMs are available at 1 arc-second (~30m), 1/3 arc-second (~10m), and 1-meter. </p>
<p><a href="https://www.usgs.gov/core-science-systems/ngp/3dep/about-3dep-products-services?qt-science_support_page_related_con=0#qt-science_support_page_related_con">USGS 3DEP Standard DEMs</a> represent the topographic surface of the earth and contain flattened water surfaces. Each DEM dataset is identified by its horizontal resolution and is produced to a consistent set of specifications. The elevations in these DEMs represent the topographic bare-earth surface (a.k.a. Digital Terrain Model (DTM)). Standard DEMs are characterized either as <em>project-based</em> or <em>seamless</em>. Project-based DEMs (e.g. 1-meter) are available for the full areal extents of projects when produced from lidar. Seamless DEMs (e.g. 1/3 arc-second and 1 arc second) are produced by blending only the highest quality project data into a continuous terrain surface for the U.S., and are updated continuously to integrate newly available, improved elevation source data.</p>
<p><strong>Seamless DEMs</strong></p>
<ul>
<li><strong>1/3 arc-second:</strong> This is the highest resolution seamless DEM dataset for the U.S. with full coverage of the 48 conterminous states, Hawaii, and U.S. territories. Alaska coverage is partially available and is being expanded to statewide coverage as part of the Alaska Mapping Initiative. Ground spacing is approximately 10 meters north/south, but variable east/west due to convergence of meridians with latitude.</li>
<li><strong>1 arc-second:</strong> This is a lower resolution seamless dataset providing complete coverage over the conterminous U.S. and partial coverage of Alaska. Most of Canada and Mexico are also covered by the 1 arc-second dataset. Ground spacing is approximately 30 meters north/south, but variable east/west depending on latitude</li>
</ul>
<p><strong>Project-based DEMs:</strong></p>
<ul>
<li><strong>1-meter:</strong> This dataset was introduced in 2015 with limited coverage of the U.S., but will be expanding as new DEMs from 3DEP quality level 2 or better lidar data are acquired.  This dataset is available to our academic users <u>(</u> i.e. <a href="https://portal.opentopography.org/login" target="_blank" title="OpenTopography login">registered OpenTopography users</a> with an account associated with a valid .edu email address). Non-academic users can access this data with a paid subscription to <a href="https://opentopography.org/plus" target="_blank">OT+ (OpenTopography Plus)</a>.</li>
</ul>
<p>OpenTopography access to USGS 3DEP DEMs leverages the <a href="https://apps.nationalmap.gov/tnmaccess/" target="_blank">USGS National Map API </a> as well as recent USGS efforts to <a href="https://www.usgs.gov/news/usgs-digital-elevation-models-dem-switching-new-distribution-format" target="_blank">migrate 3DEP DEM data to Cloud Optimized GeoTIFF (COG) format</a> hosted on <a href="https://prd-tnm.s3.amazonaws.com/index.html?prefix=StagedProducts/" target="_blank">Amazon Web services (AWS)</a>. All USGS Standard DEM data requests through OpenTopography will subset the USGS rasters from AWS on-the-fly and return a seamless, raster mosaic based on a user's area of interest. This API-based approach ensures that OpenTopography users have access to the most recently available USGS 3DEP topographic data. Please note that this service relies on external USGS services beyond OpenTopography control and thus outages may be possible.</p>
<hr />
<p><strong>Get the data:</strong></p>
<ul>
<li><strong><a href="https://doi.org/10.5069/G9NP22NT" target="_blank">USGS 1 meter Digital Elevation Model</a></strong></li>
<li><strong><a href="https://doi.org/10.5069/G98K778D" target="_blank">USGS 1/3 arc-second (~10 m) Digital Elevation Model</a></strong></li>
<li><strong><a href="https://doi.org/10.5069/G9HX19WN" target="_blank">USGS 1 arc-second (~30 m) Digital Elevation Model</a></strong></li>
</ul>
<p></p>
<p class="rtecenter"><a href="https://object.cloud.sdsc.edu:443/v1/AUTH_opentopography/www/images/NED1m_MtAdamsonGE.png" target="_blank"><img alt="USGS 1m DEM - Mt Adams" src="https://object.cloud.sdsc.edu:443/v1/AUTH_opentopography/www/images/NED1m_MtAdamsonGE.png" style="border: 0;" /></a><br /> <em>Colored hillshade of 1m DEM of Mt Adams, Washington.  Hillshade is draped on Google Earth imagery.</em></p>
<hr />

<p class="rtecenter"><a href="https://object.cloud.sdsc.edu:443/v1/AUTH_opentopography/www/images/RMNPPeaks.png" target="_blank"><img alt="USGS 10m DEM - RMNP" src="https://object.cloud.sdsc.edu:443/v1/AUTH_opentopography/www/images/RMNPPeaks.png" style="border: 0;" /></a><br /> <em>Hillshade of 10 m (1/3 arc-second) DEM of peaks within the Rocky Mountain National Park, Colorado.  Hillshade is draped on satellite imagery.</em></p>
<hr />

<p class="rtecenter"><a href="https://object.cloud.sdsc.edu:443/v1/AUTH_opentopography/www/images/AlaskaRange_30m.png" target="_blank"><img alt="USGS 30m DEM - Alaska Range" src="https://object.cloud.sdsc.edu:443/v1/AUTH_opentopography/www/images/AlaskaRange_30m.png" style="border: 0;" /></a><br /> <em>Hillshade of 30 m (1 arc-second) DEM of the Alaska Range, Alaska.  Hillshade is draped on satellite imagery.</em></p>
<hr />

</div></div></div>
