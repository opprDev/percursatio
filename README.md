# percursatio
Travel Blog

[Font awesome icons not showing in Wordpress after site address URL change](https://stackoverflow.com/questions/39077053/font-awesome-icons-not-showing-in-wordpress-after-site-address-url-change)

```
function wpb_load_fa() {

wp_enqueue_style( 'wpb-fa', 'https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css' );

}

add_action( 'wp_enqueue_scripts', 'wpb_load_fa' );
```
