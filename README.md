

```ruby

class Carson < HappyDude
  def initialize
    @hobbies = [ 'Writing', 'Podcasting', 'Language-ing' ]
    @interests = [ 'EV Supply Chain', 'History of: International Trade, China, Portugal, Brazil, Colonialism' ] 
    @languages = ['English', 'Mandarin', 'Portuguese']
    @education = [ 'Le Wagon Lisbon', 'PKU Yenching Academy', 'Middlebury Language Schools', 'Oklahoma State' ]
  end

  def currently
    {
      reading: [ 'The Clean Coder by Robert Martin', 'National Blueprint for Lithium Batteries 2021-2030', 'Diary of a Madman by Lu Xun']
      writing: [ 'Untitled stories', 'Poems about farming', 'Rendezvouz' ]
      listening: [ 'The British in India by David Gilmour', 'Darknet Diaries by Jack Rhysider', 'DHH Podcasts']
      speaking: [ 'The Carson Mulligan Podcast' ]
      studying: [ 'How to make EV batteries', 'How to move EV batteries', 'How to speak Spanish' ]
      tinkering: [ 'Ruby on Rails', 'JavaScript', 'Fukuoka Farming' ]
     }
  end
end
```
