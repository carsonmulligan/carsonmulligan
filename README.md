

```ruby

class Carson < HappyDude
  def initialize
    @tools = [ 'Ruby on Rails', 'APIs', 'Energy, Agriculture, & Logistics Data' ]
    @interests = [ 'Changing Supply Chains', 'Air Freight Logistics' ] 
    @languages = [ 'English', 'Mandarin', 'Portuguese']
    @education = [ 'Le Wagon Lisbon', 'PKU Yenching Academy', 'Middlebury Language Schools', 'Oklahoma State' ]
    @hobbies = [ 'Writing', 'Podcasting', 'Language-ing' ]
  end

  def currently
    {
      reading: [ 'Namibian Sketches by Joseph R. Nostrand' ]
      writing: [ 'Untitled stories', 'Fun poems', 'Rendezvouz' ]
      listening: [ 'Darknet Diaries by Jack Rhysider' ]
      speaking: [ 'Freestyle Rap', 'To the homies', 'The Carson Mulligan Podcast' ]
      studying: [ 'How to move freight better', 'How to speak Spanish' ]
      tinkering: [ 'Fukuoka Farming', 'Wildflower Seed Bombs' ]
     }
  end
end
```
