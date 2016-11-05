---
layout: post
title:  "apple script"
date:   2016-11-05 11:00:00 +0900
categories: program

---


apple script 로 firefox 열기



>
	on run {input, parameters}
>	
	tell application "Firefox"
>		
		activate
		open location "http://google.com/"
	end tell
	return input
>	
	end run
	
	
	
다음 두개를 참고했음.
	
http://macnews.tistory.com/537

	
	
http://stackoverflow.com/questions/3645763/how-do-i-instruct-applescript-to-open-a-new-firefox-window-with-a-link