

```ruby

class Carson < HappyDude
  def initialize
    @tools = [ 'Ruby on Rails', 'APIs', 'Energy, Agriculture, & Logistics Data' ]
    @interests = [ 'Lithium Batteries', 'Semiconductors', 'Cloud computing hardware' ] 
    @languages = [ 'English', 'Mandarin', 'Portuguese']
    @education = [ 'Le Wagon Lisbon', 'PKU Yenching Academy', 'Middlebury Language Schools', 'Oklahoma State' ]
    @hobbies = [ 'Writing', 'Podcasting', 'Language-ing' ]
  end

  def currently
    {
      reading: [ 'Foundation by Isaac Asimov', 'The Clean Coder by Robert Martin' ]
      writing: [ 'Untitled stories', 'Fun poems', 'Rendezvouz' ]
      listening: [ 'Darknet Diaries by Jack Rhysider', 'Tim Ferriss']
      speaking: [ 'Freestyle Rap', 'To the homies', 'The Carson Mulligan Podcast' ]
      studying: [ 'How to make EV batteries', 'How to move EV batteries', 'How to speak Spanish' ]
      tinkering: [ 'React', 'Python', 'Fukuoka Farming' ]
     }
  end
end
```
