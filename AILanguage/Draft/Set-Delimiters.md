


	:Tag :TagType
	:Tag :TagType :Property
	:Tag :TagType :Property :Property
	:Tag :TagType :Property :Property :Property
	:Tag :TagType :Property :Property :Property :Property
	:Tag :TagType [:Properties] (/PropertyTerminator)

	:String Terminator (ends a string, such as a name, title, subtitle, etc)
	:Whitespace [X Spaces]
	:Newline
	:Separator

	:Statement Start
	:Statement Terminate
	:Statement Terminate with Name

	:Sentance Terminate
	:Sentance Terminate with Newline

	:Paragraph
	:SectionStart

	:Title			// Terminates at Newline or String Terminator
	:Subtitle		// Terminates at Newline or String Terminator

	:HeaderLine :HeaderNum			// Terminates at Newline
	:CommentLine :CommentNum		// Terminates at Newline
	:BulletPoint :BulletLevel		// Terminates at Newline
	:SubBullet :SubLevel			// Terminates at Newline
	:BulletNum :BulletNumLevel		// Terminates at Newline
