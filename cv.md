# Natia shanidze

###### Contact Info
* n.shanidze9@gmail.com
* https://www.linkedin.com/in/natia-shanidze-97996790/

###### Summary
##### My desire is to develop professionally

###### Skills 
* HTML
* CSS
* JS
* PHP
* MYSQL

###### Code examples
```
public function geturls($id) {
		$str = \DB::table('articles')->where('id', $id)->first();
		$ret = array();
		foreach(config('_front.languages') as $l) :
			$p = \DB::table('articles_lang')->where('articles_id', $str->id)->where('language', $l)->first();
			$ret[$l] = config('_front.siteurl') . config('_front.sitefolder') . $l . '/' . $p->route;
		endforeach;
		return json_encode($ret);
	}
```

###### Experience
* Create Web Page

###### Education 
##### Ivane Javakhishvili Tbilisi State University

###### English
##### B2