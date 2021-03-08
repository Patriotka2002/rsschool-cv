<!doctype html><meta charset="utf-8"><meta name="viewport" content="width=device-width, initial-scale=1">
<link href='http://fonts.googleapis.com/css?family=Droid+Sans|Droid+Serif:700' rel='stylesheet' type='text/css'>
<link href='basic.css' rel='stylesheet' type='text/css'>
<div class="container">
	<header class="masthead">
		<h1>Elizabeth Ryabova</h1>
		<div class="sub_header">
			<span class="email">elizabethryabova2002@gmail.com</span>
			<span class="location">Belarus, Minsk</span>
		</div>
	</header>
	<section class="intro">
		<p>2nd year student of BSU FPMI, born on 01.10.2002, unmarried.
       + 375(44) 531-40-73 - preferred method of communication</p>
	</section>
	<section class="skills">
		<h1>Skills</h1>
	</section>
	<div class="clearfix">
		<section class="work item_list">
			<h1>Languages skills</h1>
				<div class="item">
					<div class="what">Russian, Belarusian - native</div>
          <div class="what">English - B1+</div>
          <div class="what">German – B1+</div>
		</section>
		<section class="edu item_list">
			<h1>IT skills</h1>
			<div class="item">
				<div class="what">C++</div>
				<div class="what">Java</div>
	</section>
	<section class="skills">
		<h1>Personal skills</h1>
			<ul class="primary">
				<li>Ability to analyze and make decisions
				<li>Entrepreneurship
				<li>Optimism
			</ul>
			<ul class="secondary">
				<li>Responsibility
				<li>Honesty
				<li>Ambition
				<li>Sociability
				<li>Enthusiasm
			</ul>
<h1>Achievements</h1>
			<div class="blurb"><p>Successful participation in city Olympiads in various subjects during the
period of study in gymnasium No. 50.
As a member of the gymnasium's national team, she won
volleyball and streetball competitions.
Repeatedly participated in sports competitions (squash,
swimming, skiing, basketball).
Participated in the international conference OLMUN 2018 with a report on the
topic “Cyber security” (Oldenburg, Germany).
Winner of the Republican school league of KVN 2019 as a member of the
team "Breeze".
Winner of international and national music competitions as a
member of the “TUTTI " choir.
She participated in Olympiads and competitions in English as a member of the
university team.
At the moment, I am the curator of the first course of computer
security of the FPMI from the administration of the BSU.
</p>
<h2>Education</h2>
<p>I studied at Padworth College (London, UK) in 2014.
Graduated with a red diploma from the music school No. 8 in Minsk.
Graduated with honors in 2018 from the international school of
models Jewel Models.
In 2019, I graduated from the Order of the Red Banner of
Labor Gymnasium No. 50 in Minsk with an average score of 9.6.
Currently, I am studying in the second year of BSU FPMI,
majoring in computer security (full-time, budget).
I am studying at the German language courses at the Goethe Institute in Moscow.
Minsk (current level B2).</p>

<h2>Code example</h2>

<p>```java
public static void main(String[] args) {
        if ( args.length != 2 ) {
            System.err.println("Invalid number of arguments");
            System.exit(1);
        }
        double x = Double.parseDouble( args[0] );
        if ( x > 1 || x < -1 ) {
            System.err.println("Invalid argument: " + x );
            System.exit(1);
        }
        int k = Integer.parseInt( args[1] );
        if ( k <= 1 ) {
            System.err.println("Invalid argument: " + k );
            System.exit(1);
        }
        double Eps = 1 / Math.pow( 10, k + 1 );
        double result = 0;
        double step = x;
        int n = 1;
        while( Math.abs( step ) >= Eps ) {
            result += step;
            step = (( step * x * x )/( n + 2 ));
            n++;
	}
        result = 2 * result;
        String fmt = "%." + args[1] + "f\n";
        System.out.printf( fmt, result );
        System.out.printf( fmt, Math.log( (1+x) /(1 - x) ));
        System.exit(0);
    }
```</p>
	</section>

</div>

