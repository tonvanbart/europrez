---
title: "EP30 sign up"
description: "EP30 sign up"
date: 2025-09-14T16:50:52+02:00
draft: false
---
### EP30 _PRE_-registration
Welcome to the _pre_registration for EP30, June 25-28, 2026.

Please fill out the Google Form below, providing the email address with which you are subscribed 
to the list (for easy reference).
{{<  line_break >}} 
_**Please Note: it's not necessary to log in to Google, the form will work anyway.**_

If you are a family needing more than one room, it would help the organizer if you fill in the 
form once for each room you need (so 4 people for example could ask for 1 double room and 2 singles).
{{< line_break >}}
This makes it easier for our dictator to keep track of the number and type of room needed. Thank you in advance!

The following names have already signed up (_**refresh the page to see the latest update**_):
{{<line_break>}}
{{< rawhtml >}}
<span id="names">(loading...)</span>

<script language="javascript">
        document.addEventListener('DOMContentLoaded', function() {
    fetch('https://docs.google.com/spreadsheets/d/e/2PACX-1vRqzlI_LDDCpa9nsR91szFIwBS0zNJH4AkX18AsPodSLOwL5eh94eMbmSqFry4SQ81ShU22nUHGA30I/pub?gid=99001797&single=true&output=tsv')
        .then(response => response.text())
        .then(data => {
            var lines = data.split('\n');
            var names = lines[1].split('\t')[1];
            document.getElementById('names').textContent = names;
        })
        .catch(error => {
            document.getElementById('names').textContent = "(failed to load)";
            console.error('Error loading TSV file:', error);
        });
});

</script>
{{</ rawhtml >}}


{{< rawhtml >}}
<iframe src="https://docs.google.com/forms/d/e/1FAIpQLScgXJITsQm-9G6lj5mbZgxgJgIu4zRDpyU6zk0GENIiFbfnEg/viewform?embedded=true" width="640" height="1900" frameborder="0" marginheight="0" marginwidth="0">Laden…</iframe>
{{</ rawhtml >}}
