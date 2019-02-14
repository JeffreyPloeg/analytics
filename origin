// enhanced UTM tags for internal traffic measurement

function extractParamFromHash(name, def) {
var match = new RegExp('[#&]'+name+'=([^&]+)').exec(window.location.hash);
if (match==null) return def;
  else return match[1]+"";
}

var origin = extractParamFromHash('origin', '');
var linktype = extractParamFromHash('linktype', 'click');
if (origin != '') {

  // set to variable, i.e. Tealium
  b.siteorigin = origin;
  b.originlinktype = linktype;
}
