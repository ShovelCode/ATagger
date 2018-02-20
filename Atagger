#Takes in a text file of URLs, and makes a file of hyperlinks.
print "This is the atag program\n"
textin = File.open("links.txt", "r")
textout = File.open("ataglinks.txt", "w")
while !textin.eof?
        line = textin.readline
        line2 = line.chop
        puts line2 + "\n"
        puts "Name: "
        name = gets.chomp
        textout.write "<a href=\"#{line2}>#{name}\"</a><br>\n"
 
    end
