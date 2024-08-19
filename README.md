

```ruby

class Carson < HappyDude
  def initialize
    @tools = [ 'Python', 'PySpark', 'SQL',  'Databricks', 'Ruby on Rails' ]
    @interests = [ 'Supply Chains', 'Language Acquisition' ] 
    @languages = [ 'English', 'Mandarin', 'Portuguese', 'French', 'Spanish', 'Italian']
    @hobbies = [ 'Writing', 'Podcasting', 'Language Learning' ]
  end

  def currently
    {
      reading: [ 'Lots of stuff about Planets and Stars' ]
      writing: [ 'Comments in Databricks' ]
      listening: [ 'Ted Talks in Italiano' ]
      speaking: [ 'Freestyle Rap', 'To the homies', ]
      studying: [ 'Freight moving', 'Documentari di Astrofisica' ]
      tinkering: [ 'Guerilla gardening' ]
     }
  end
end 
```
