# Firefly
Debugging Page for PHP

## Usage
```php
try {
	//code...
} catch (\Throwable $th) {
	Firefly::AppFire($th, "Source\of\the\exception");
}
```
