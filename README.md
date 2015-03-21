# [Array Exercise](https://materials.generalassemb.ly/bewd/new-york-city/20/lessons/3#classwork)

First, fork [this](https://github.com/BEWD-NYC-20/arrays) repository and run:

```bash
cd ~/Sites/
git clone https://github.com/your-username-here/arrays.git
```

Next, copy the following code into sublime text, and save it as
`~/Sites/arrays/your_name_here/arrays.rb`:

```ruby
# Array Exercise
#
# Edit the contents of `top_right`, `bottom_center` and `center`
# according to the comments in each of the methods. Once completed, run this
# file from your terminal (remember, we use the `ruby` command), and you should
# see a success or failure message for each.
#

matrix = [
  [0, 1, 2],
  [3, 4, 5],
  [6, 7, 8]
]

def top_right(matrix)
  # This method should return (not puts) the number all the way to the top
  # right of the variable `matrix`
end

def bottom_center(matrix)
  # This method should return (not puts) the number all the way to the bottom
  # left of the variable `matrix`
end

def center(matrix)
  # This method should return (not puts) the array in the middle of the `matrix`
end

if top_right(matrix) == 2
  puts 'SUCCESS: You got the top right element!'
else
  puts "It looks like the `top_right` method isn't returning the right value"
end

if bottom_center(matrix) == 7
  puts 'SUCCESS: You got the bottom center element!'
else
  puts "It looks like the `bottom_center` method isn't returning the right value"
end

if center(matrix) == [3, 4, 5]
  puts 'SUCCESS: Congratulations, you finished the exercise'
else
  puts "It looks like your `center` method isn't reutrning the right value"
end
```

Follow the instructions in the comments, and when you are finished, save the
file, commit the code to Git and push it to GitHub:

```bash
cd ~/Sites/arrays/
git add your_name_here/arrays.rb
git commit -m "Adding array exercise"
git push origin master
```
