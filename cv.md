#Elena Markova

##PHP Web Developer

**fireleit@gmail.com	+995 551 51 0841**
[LinkedIn](https://www.linkedin.com/in/fireleit/)    [Website](https://gagara-web.ru/about/portfolio/)


###Summary

Development experience - over 5 years. Worked in a team and also managed my own web studio. Professionally engaged in the development of web applications, modules, and extensions for websites and CMS. Develope APIs and integrate third-party APIs into projects.


###Professional Skills

*PHP
*Laravel Framework
*SQL
*Git
*Docker
*Composer
*API Development
*RESTful Services
*SOAP Protocol
*Web Services
*Wordpress API
*1C-Bitrix framework	
*OpenCart
*MODx
*Magento	

 
###Code example

```
<?php

class BaseAjax
{    
    protected $post;
    protected $success;
    protected $output;

    
    public function __construct(array $post)
    {

        $this->post = $post;
        $this->success = false;
        $this->output = __('Errors occurred during script execution. Please inform the site administrator about this issue', 'lasertag');
    }


    protected function validate(): bool
    {

        if(!empty($this->post)) {

            return true;
        }
        return false;
        
    }


    protected function setSuccess() {
        $this->success = true;
    }

    protected function setUnSuccess() {
        $this->success = false;
    }

    protected function setOutputMessage(string $message) {
        $this->output = $message;
    }
        
    public function is_success(): bool
    {
        return $this->success;
    }

    public function get_output()
    {
        if($this->validate()){

            $this->setSuccess();
            
        }

        return json_encode(['success' => $this->success, 'output' => $this->output]);
    }

}
```


###Work experience

**OOO	"MAST", IT Company (Moscow, Russia)**
__Web Developer__
__03/2022 - present__

*Web application development
*Working with designers and front-end developers
*API implementing


**Sole Proprietor**
__Web Studio Head__
__04/2020 - present__

*Developed and maintained web applications and API using PHP
*Optimized web applications performance
*Implemented new features and improved user interfaces
*Integrated third-party services and APIs
*Supported and improved existing projects
*Collaborated with designers and front-end developers to create turnkey apps


**OOO	"Sushi Krai", Food Delivery Company (Voronezh, Russia)**
__Miidle Web Developer__
__02/2021 - 12/2021__

*1С database integration
*Creating API for web and mobile application (ecommerce)
*Customer loyality program development and implementation



###Education			
						
Irkutsk State University	
2000 - 2005
Commerce (Specialist Degree)



###Projects			
						
**sushikrai.ru**
A sushi and rolls online store. Integration with 1C database, API development for web and mobile applications, customers loyalty program development, third-party APIs integration

**letk.ru**
A transportation company's website. Includes a cargo transportation calculator,	third-party APIs integration

**millturn.ru**
A metalworking equipment online store. 1C integration

**xn--80acbooaruzw.xn--p1ai**
A  real-life  quests  website  with  a  booking  system.  Integration  with  quest aggregator APIs

**Other projects**
More examples you can see on my web studio page:	
https://gagara-web.ru/about/portfolio/


###Languages

Russian - Native
English - Intermediate