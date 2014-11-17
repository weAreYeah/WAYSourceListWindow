WAYSourceListWindow
===================

The WAYSourceListWindow is a NSWindow subclass, which splits the window space vertically into the master view on the left, and the detail view on the right side as known from apps like Reminders or Notes.

The window uses a NSSplitView for the splitting. You should add subviews to instances of this class by setting the masterView and detailView, e.g., via the IBOutlets in Interface Builder. These views will then be added as subviews internally to the masterViewWrapper or detailViewWrapper.

By default, the Master View uses a Vibrant Light appearance. You can change this as you desire.

Whenever it makes sense, the properties of your WAYSourceListWindow instance in Interface Builder are inspectable.

Example
-------

![WAYSourceListWindow](WAYSourceListWindow%20Example.png)

Usage
-----

1. Drag a new ```NSWindow``` instance to your XIB
2. Set the class of the instance to ```WAYSourceListWindow```
3. Customize the properties via Interface Builder or programmatically
4. Create two new ```NSView``` instances in Interface Builder
5. Right-click-drag from your ```WAYSourceListWindow``` instance to one of the views and define it as the Master View.
5. Right-click-drag from your ```WAYSourceListWindow``` instance to one of the views and define it as the Detail View.

Explanation
-----------

![WAYSourceListWindow](WAYSourceListWindow.png =350x)


Interesting
-----------
We are new, weAreYeah.com.
Follow us on [@weAreYeah](http://twitter.com/weAreYeah) for upcoming goodies.

License
-------
Licensed under the BSD License <http://www.opensource.org/licenses/bsd-license>
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY
EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES
OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT
SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT,
INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED
TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR
BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT,
STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF
THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.


![We are Yeah!](http://www.weAreYeah.com/weAreYeah@2x.png)
