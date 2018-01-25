<?php
/*
This Code Was created by Akbar
RECODE By LeeProject
THIS SCRIPT IS FREE - NOT FOR SALE
*/
date_default_timezone_set('Asia/Jakarta');
error_reporting(0);
set_time_limit(0);
ini_set('memory_limit', '-1');
ini_set('output_buffering',0); 
ini_set('request_order', 'GP');
ini_set('variables_order','EGPCS');
ini_set('max_execution_time','-1');
ini_set('user_agent', 'Mozilla/5.0 (Linux; Android 6.0; E1C 3G Build/MRA58K) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/56.0.2924.87 Mobile Safari/537.36');
if (date("H") >= 4){
$url = array(
'http://freesatoshi4all.xyz/faucet.php?coinhive-captcha-token=i8OWDLbAlQ0LuHteY2dvNCHGkPUQ3unC&address=D8WqLiwqieK7Le4kMTawDzsThnMwpD5nNJ&currency=DOGE&key=e14fda4f6ec21eb297eedaab782b660c',
'http://japakar.com/auto5/faucet.php?address=0x65725e70e1a5c017d3c2f84b652bf4ee0adcb363&currency=ETH&key=207faed8713f634e41fe0e0f36cc654c',
'http://faucet-mining.club//faucet.php?address=1AkKzpBcb4pbFv14Se6rtzJ2ojuRNErfw2&currency=BCH&key=0b4a12298739a0c5b93b707e01eacdc1',
'http://floodcoins.xyz/faucet.php?address=17Mh5AkBE6Qzit1PxqVtQpRnA4e8oFDzgj&currency=BTX&key=f69ee0f51c1c00ee3bc0e54912735b96',
'http://floodcoins.xyz/faucet.php?address=D8WqLiwqieK7Le4kMTawDzsThnMwpD5nNJ&currency=DOGE&miner=on&key=d0d4ad8e511cdb359298383c9bd829ce',
'http://japakar.com/auto2/faucet.php?address=D8WqLiwqieK7Le4kMTawDzsThnMwpD5nNJ&currency=DOGE&key=1b1193cdad4218aab449292d3a60bcfb',);
foreach($url as $link){
	$ch = curl_init();
    curl_setopt($ch, CURLOPT_URL, $link);
    curl_setopt($ch, CURLOPT_RETURNTRANSFER, 1);
    curl_setopt($ch, CURLOPT_REFERER, 'https://google.com');
    curl_setopt($ch, CURLOPT_USERAGENT, 'Mozilla/4.0 (compatible; MSIE 7.0; Windows NT 6.1; Win64; x64; Trident/4.0; Mozilla/4.0 (compatible; MSIE 6.0; Windows NT 5.1; SV1) ; NeoDownloader Embedded Web Browser from: http://bsalsa.com/; .NET CLR 2.0.50727; SLCC2; .NET CLR 3.5.30729; .NET CLR 3.0.30729)');
    curl_setopt($ch, CURLOPT_COOKIEJAR, 'cookie');
    curl_setopt($ch, CURLOPT_COOKIEFILE, 'cookie');
    $data = curl_exec($ch);
    curl_close($data);
    $one = explode('<div class="alert alert-success">', $data);
    $two = explode('</div>', $one[1]);
    $pr = "$two[0]\n";
    echo $pr;
}
}else{
echo "Time to Sleep and have  a nice dream";
}
?>
