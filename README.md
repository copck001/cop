# cop
header('Access-Control-Allow-Origin: *');
header('Access-Control-Allow-Methods: GET, POST, OPTIONS');
header('Access-Control-Allow-Headers: Origin, Content-Type, Accept, Authorization, X-Request-With');
header('Access-Control-Allow-Credentials: true');

function __construct()  -- Controller
		{
			parent::__construct();
			$this->load->model('cg_model');
		}
    
    function __construct() -- model
	{
		parent::__construct();
		$this->load->database();
	}

$param = file_get_contents("php://input");
			$request = json_decode($param);
      
      
      https://ng-bootstrap.github.io/#/components/table/examples
