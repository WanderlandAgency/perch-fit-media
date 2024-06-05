This is a database for background videos of Perch Fit website.

To add a video on GitHub go to "<>code" tab in the top left corner and click "add files" (at the left of "<> code" green button).
Then when you're done, click on "commit changes" (green button)

Go to jsDelivr website (https://www.jsdelivr.com/?docs=gh) and make sure you're on the "GitHub" tab

We get this link:
https://cdn.jsdelivr.net/gh/user/repo@version/file

Let's copy and paste this into a note file to customize it a bit and make it work.

Replace /user/ by your username (in my case it's /mlleourse/)
Replace /repo@version/ by the repository name (here it is /perch-media/)
Replace /file by the filename of your asset with the extension

Example:
https://cdn.jsdelivr.net/gh/mlleourse/perch-media/perch_plan_raw_576p.mp4

Copy and Paste this link into the src attribute of your <video> tag

And voilà!

PS: Upload mp4 and webM versions of a file, so we get a fallback if the user's browser does not support the codec.
PS2: Firefox does not support .mp4 files encoded in h265 (but supports webM) while Chrome and Chromium browsers do.
