Forking a vivid software project is usually a bad thing and there are
only few reasons when this action is considered legitimated.
The most common of those reasons is a licence change of the project -
this is what happened here.<br>
The main author of this great piece of software, Rick Brewster, decided<br>
to change the licence for all further releases of Paint.NET <a href='http://blog.getpaint.net/2009/11/06/a-new-license-for-paintnet-v35/'>[1</a>] making<br>
this version the last one to licensed under MIT Licence (with exceptions<br>
for Artwork and the GPC library, limiting the whole software to<br>
non-commercial distribution, see src/Resources/Files/License.txt).<br>
<p>Any further releases include the restrictive clause<br>
"You may not modify, adapt, rent, lease, loan, sell, or create<br>
derivative works based upon the Software or any part thereof."</p>
One year has passed since the last free sources of the project had been<br>
released, giving the authors time to change their minds.<br>
Their decision has to be respected, but the OpenSource community still<br>
has to be able to build upon the last version of this powerful tool.<br>
<br>
Main goals of this fork are:<br>
<ul><li>Linux port (which means porting it to mono basically)<br>
</li><li>replacing non-free parts (Artworks, General Polygon Clipper as those are only usable non-commercially, making this non-free software in the sense of OSI <a href='http://opensource.org/docs/osd'>[2</a>])</li></ul>

Of cause, all credits to the initial authors will remain, naturally new<br>
contributors will be credited as well.<br>
<br>
<b>If you are looking for a photo editing software for Windows, you may want to use the original <a href='http://www.getpaint.net/'>Paint.NET</a> as it has more features and might be better supported. The main focus of this project is to establish portability</b> (and keep the last free Paint.NET code publicly availiable)