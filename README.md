## hackerrank-bookmarklet

A [bookmarklet](javascript: (() => {
  // can I haz right click and copy?
  $(document).off('contextmenu cut copy paste')

  // CTRL+ALT runs tests
  document.onkeydown = e => {
    const evtobj = window.event? event : e
    if (evtobj.keyCode == 13 && evtobj.ctrlKey) $('.bb-compile').click()
  }
})()) to speed up things a bit
