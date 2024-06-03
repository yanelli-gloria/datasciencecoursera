fileConn <- file("HelloWorld.md")
writeLines("## This is a markdown file", fileConn)
close(fileConn)
