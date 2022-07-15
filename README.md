

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
      reading: [ 'The Clean Coder by Robert Martin', 'National Blueprint for Lithium Batteries 2021-2030', 'Diary of a Madman by Lu Xun']
      writing: [ 'Untitled stories', 'Fun poems', 'Rendezvouz' ]
      listening: [ 'The British in India by David Gilmour', 'Darknet Diaries by Jack Rhysider', 'DHH Podcasts']
      speaking: [ 'Freestyle Rap', 'To the homies', 'The Carson Mulligan Podcast' ]
      studying: [ 'How to make EV batteries', 'How to move EV batteries', 'How to speak Spanish' ]
      tinkering: [ 'React', 'Python', 'Fukuoka Farming' ]
     }
  end
end
```
