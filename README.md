# Udacity-tournament-result

---

## Introduction

Udacity Tournament Result is a project for the course "Intro to Relational Database". The module contains codes that keeps track of users and matches in a swiss-style tournament. This program is great for 2^n many players. The program uses psycopg2 library, and python.

## Step-by-step Instruction

### 1. Downloading File

#### Windows

1. Install [git bash](https://git-scm.com/downloads) 
2. Open git bash
3. Navigate to a directory of choice
4. Type `git clone https://github.com/hyungmogu/udacity-tournament-result/`; clone the repository

#### Linux/MacOS

1. Open terminal
2. Navigate to a directory of choice
3. Type `git clone https://github.com/hyungmogu/udacity-tournament-result/`; clone the repository

### 2. Installing Vagrant

1. Download and install [Virtual Box](https://www.virtualbox.org/)
2. Download and install [Vagrant](https://www.vagrantup.com/downloads.html)
  - NOTE: Ubuntu is a [Debian-based operating system](https://en.wikipedia.org/wiki/Ubuntu_(operating_system)).
3. Boot into BIOS and enable virtual environment
  - NOTE: This step varies for different motherboard models and versions. Please refer to instruction provided by manufacturer for details.  

### 3. Running Vagrant3

#### Windows
1. 

#### Linux/MacOS

1. Open terminal
2. Navigate to the directory where cloned repo is located
3. Type `vagrant up` in `Vagrant` folder containing 'Vagrantfile'
4. Type `vagrant ssh` and log into the virtual machine

### 4. Running Project File (In Vagrant)

1. Type `cd /vagrant/tournament/` after logging in
2. Type `python`; run python
3. Type `import tournament` in python shell; import functions from the module

## Functions

### deleteMatches()
Removes all match records from database.

### deletePlayers()
Removes all player records from database.

### countPlayers()
Returns the number of registered players.

### registerPlayer(name)
Adds a player to the tournament database.

### playerStandings()
Returns a list of the players and their win records, sorted by wins.

### reportMatch(winner_id,loser_id)
Records the outcome of a single match between two players.

### swissPairings()
Returns a list of pairs of players for the next round of a match.


   
