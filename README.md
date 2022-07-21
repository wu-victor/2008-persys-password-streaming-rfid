# 2008 PerSys Workshop Paper

Password Streaming for RFID Privacy

https://link.springer.com/chapter/10.1007/978-3-540-88875-8_113

## Abstract

We propose a novel privacy-protecting RFID system using password streaming. Our scheme assumes a centralized back-end system containing a database of tag passwords. A reader uses this database to broadcast password “guesses” continuously in its domain, without it needing to scan for the presence of tags. A tag that receives a matching password tells the reader it is present, and the password is replaced with a new one that is synchronized both in the tag and the database. Our scheme also assumes multiple readers with their respective domains in a large physical space. As tags and attackers (adversaries intent on compromising privacy) move between domains, the back-end system coordinates the readers’ password streams to defend against attacks. Our scheme pushes the computational complexity to the back-end system, very much in the spirit of RFID. It defends against stronger types of attacks than those in [4].