

```ruby

class Carson < HappyDude
  def initialize
    @education = [ 'Le Wagon Lisbon', 'PKU Yenching Academy', 'Middlebury Language Schools', 'Oklahoma State' ]
    @hobbies = [ 'Writing', 'Podcasting', 'Language-ing' ]
    @interests = [ 'History of International Trade', 'Electrification & EV Supply Chain', 'History of Colonialism' ] 
    @languages = ['English', 'Mandarin', 'Portuguese']
  end

  def currently
    {
      reading: [ 'The Clean Coder by Robert Martin', 'National Blueprint for Lithium Batteries 2021-2031', 'Mad Man's Diary by Lu Xun']
      listening: [ 'The British in India by David Gilmour', 'Darket Diaries by Jack Rhysider', 'DHH Podcasts']
      studying: [ 'How to make EV batteries', 'How to move EV batteries', 'How to speak Spanish' ]
      tinkering: [ 'Ruby on Rails', 'JavaScript', 'Fukuoka Farming' ]
     }
  end
end
```
