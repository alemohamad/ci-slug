# CodeIgniter Library: Create new and unique slugs

**ci-slug**

## About this library

This CodeIgniter's Library is used to create new and unique slugs.  

The method will search in the database for an preexistent slug, and if it exists it will increment the final number to return a new and unique slug.  

This project is a modified version of the Farhan Khan's [CodeIgniter Slug Library](https://github.com/farkhan/codeigniter-slug-generator).  

Its usage is recommended for CodeIgniter 2 or greater.  

## Usage

```php
$this->load->library('Slug');

// parameters: 'text', 'table'
echo $this->slug->create_unique_slug('New features in GitHub', 'news');
```

![Ale Mohamad](http://alemohamad.com/github/logo2012am.png)
