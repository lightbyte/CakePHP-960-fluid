# CakePHP 960-fluid

A 960 based theme for CakePHP 2.1

##Installation


clone the repo to the 
 * app/View/Themed/ directory


To switch the theme try this in your AppController

class AppController extends Controller {
	public $viewClass = 'Theme';

		....



	function beforeFilter() {
		parent::beforeFilter();
		$this->theme='960-fluid';
	}
