# README

this project demonstrates issue with administrate gem not able to work with a model named `Host`

```
ActionController::UnfilteredParameters in Admin::Hosts#index
Showing /Users/jurgen/.rbenv/versions/3.4.4/lib/ruby/gems/3.4.0/gems/administrate-0.19.0/app/views/administrate/application/_collection.html.erb where line #31 raised:

unable to convert unpermitted parameters to hash

        convert_parameters_to_hashes(@parameters, :to_h, &block)
      else
        raise UnfilteredParameters
      end
    end
```
