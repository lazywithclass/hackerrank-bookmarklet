## hackerrank-bookmarklet

A [bookmarklet](javascript: (() => {$(document).off('contextmenu cut copy paste');document.onkeydown = e => {const evtobj = window.event? event : e; if (evtobj.keyCode == 13 && evtobj.ctrlKey) $('.bb-compile').click();}})()
) to speed up things a bit
