## Readme

This is a **QRCode** library for **Codeigniter** 2.x.


## Useage
Put `bb_qrcode.php` into your `applications/libraries/` and put directory `qrcode` in somewhere. then use it like this:
	
    $this->load->library('bb_qrcode');
    
    $str = 'http://foo.bar';
    $this->bb_qrcode->generateQRCode($str);


