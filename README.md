itaiji
------

Convert japanese itaiji(異体字) to seijitai(正字体) or reverse also.

Instration
----------

Add this line to your application's Gemfile:

    gem 'itaiji'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install itaiji

Usage
-----

```
converter = Itaiji::Converter.new
converter.convert_seijitai('髙橋') # => '高橋'

converter.convert_itaiji('高橋') # => '髙橋'
```

Source
------
http://wwwap.hi.u-tokyo.ac.jp/ships/itaiji_list.jsp