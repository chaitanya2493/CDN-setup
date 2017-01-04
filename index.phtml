<?php 
const INI_LOCATION = 'application.ini';
$cdn_domain = $_SERVER['SERVER_NAME'];
$cdn_version = 1;
$ini_array =array();
if(file_exists(INI_LOCATION) == true){
	$ini_array = parse_ini_file ( INI_LOCATION );
	if(! empty ($ini_array ['CDN_DOMAIN'])){
		$cdn_domains = explode(',', $ini_array['CDN_DOMAIN']);
		$cdn_domain = $cdn_domains[array_rand($cdn_domains)];
	}
	if(! empty ($ini_array ['CDN_VERSION'])){
		$cdn_version = $ini_array['CDN_VERSION'];
	}else{
		$cdn_version = 0;
	}
}
define("CDN_DOMAIN", $cdn_domain);
define("CDN_VERSION", $cdn_version);

function getCdnUrl($content){
	$url = '//'. CDN_DOMAIN . '/' . CDN_VERSION .'/'. $content;
	return $url;
}
?>
<html>
<head>
<link href="<?php echo getCdnUrl('css/style.css'); ?>" rel="stylesheet" type="text/css" />

</head>
<body>
<h1 class="header">Content Delivery Network</h1>
<p class="paragraph">Access domain url from the ini file</p>
</body>
</html>
