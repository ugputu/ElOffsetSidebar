ElOffsetSidebar
===============

jQuery plugin to make Offcanvas sidebar

YT("ggQyHoUowaE", print = TRUE)



Example:
  - i take simple bootstrap example with sidebar
  - append div with id el-sidebar-nav after body tag
  - wrap all contents to div with id "el-wrapper"
  - add show sidebar button ( a with classed "btn btn-success el-sidebar-btn" and some image)
  - add hide button at top of original sidebar contents ( a with classes "btn btn-success el-sidebar-btn" and image)
  - insert script link at bottom (el-offsidebar.js)
  - after link add code 		
  - [code]	$.fn.elSidebar({
		sidebar		: '.blog-sidebar',			// real sidebar
		sidebarBtn	: '.el-sidebar-btn',		// show/hide sidebar button
		elSidebar	: '#el-sidebar-nav',		// el sidebar
		elWrapper	: '#el-wrapper'				// el wrapper
	});
[/code]
