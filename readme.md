jQuery Form Savior Plugin by Anand Gorantala, Arrowconcept.com

a jQuery plugin to prompt save of unsaved changes in form when the user is navigating away.


LICENSE
-------



This work is licensed under Creative Commons Attribution Sharealike 3.0


REQUIREMENTS
------------



You will of course need jQuery(http://jquery.com) to run this. This is a jQuery plugin after all   


USAGE
-----

It is quite straightforward. Simplest usage is 

	$(document).ready(function() {
		$("form").formSavior();
	});
		
Use any selector for 'form' or just leave it as is and it will apply the check for all the forms on the page. See, Simple!

		
The plugin has one option, msg, to customize your message for each form. Its usage is shown below.

	$(document).ready(function() {
		$("#personInfo").formSavior({
			'msg' : 'Personnel information changes have not been saved.'
		});
	});

		
		
		
		
------------------------------------------------------------------------------------------------------		
NO WARRANTY

THE WORK IS PROVIDED "AS IS," AND COMES WITH ABSOLUTELY NO WARRANTY, EXPRESS OR IMPLIED, TO THE EXTENT PERMITTED BY APPLICABLE LAW, INCLUDING BUT NOT LIMITED TO THE IMPLIED WARRANTIES OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE.

------------------------------------------------------------------------------------------------------
DISCLAIMER OF LIABILITY.

IN NO EVENT SHALL THE AUTHOR OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS WORK, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE

