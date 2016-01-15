License
-------

If the software submitted to this repository accesses or calls any software provided by Plex (“Interfacing Software”), then as a condition for receiving services from Plex in response to such accesses or calls, you agree to grant and do hereby grant to Plex and its affiliates worldwide a worldwide, nonexclusive, and royalty-free right and license to use (including testing, hosting and linking to), copy, publicly perform, publicly display, reproduce in copies for distribution, and distribute the copies of any Interfacing Software made by you or with your assistance; provided, however, that you may notify Plex at legal@plex.tv if you do not wish for Plex to use, distribute, copy, publicly perform, publicly display, reproduce in copies for distribution, or distribute copies of an Interfacing Software that was created by you, and Plex will reasonable efforts to comply with such a request within a reasonable time.

# Installation

Follow [manual installation instructions ](https://support.plex.tv/hc/en-us/articles/201187656-How-do-I-manually-install-a-channel-)from here.

# Information for developer
* Requesting for a json with all station for a user: `curl 'http://tunein.com/profile/follows/?identifier=u159012873/follows/stations&type=&offset=20' -H 'x-requested-with: XMLHttpRequest'`
* [Setting header to HTTP Request](http://thingsinjars.com/post/297/writing-a-plex-plugin-part-i/)
* [Persisting channel information](http://forums.plex.tv/discussion/88179/storing-user-data-in-dict)

curl 'http://tunein.com/userprofile/contents/?username=adamchuk2168' -H 'x-requested-with: XMLHttpRequest'

curl 'http://tunein.com/profile/follows/?identifier=u159012873/follows/stations&type=&offset=40' -H 'x-requested-with: XMLHttpRequest'

http://tunein.com/user/adamchuk2168/
