## Readme

This is a **QRCode** library for **Codeigniter** 2.x.


## Useage
Put `bb_qrcode.php` into your `applications/libraries/` and put directory `qrcode` in somewhere. then use it like this:
	
    $this->load->library('bb_qrcode');

    $url = 'http://foo.bar';
    
	$params['data'] = $url;
	$params['level'] = 'M';
	$params['size'] = 6;
	$params['savename'] = FCPATH.'static/qrcode/qrocde.png';
	$this->bb_qrcode->generate($params);

