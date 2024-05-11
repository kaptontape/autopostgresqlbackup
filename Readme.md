# AutoPostgreSQLBackup

AutoPostgreSQLBackup is a shell script (usually executed from a cron job) designed to provide a fully automated tool to make periodic backups of PostgreSQL databases.

AutoPostgreSQLBackup extract databases into flat files in a daily, weekly or monthly basis.

Version 2.0 is a full rewrite.

It supports:
 * Email notification
 * Compression on the fly
 * Encryption on the fly
 * Rotation (daily and/or weekly and/or monthly)
 * Databases exclusion
 * Pre and Post scripts
 * Local configuration

## Usage

On Debian (or derived):

Install: `apt install autopostgresqlbackup`

That's it!

## Documentation

See [the documentation](/Documentation.md).

## History

 * 2023: Almost full rewrite with better error handling and new features (see Changelog.md for details)
 * 2019: Creation of a fork/standelone project on Github (https://github.com/k0lter/autopostgresqlbackup)
 * Since 2011: Various patches (fixes and new features) were added in the Debian package
 * 2011: AutoPostgreSQLBackup was included in Debian
 * 2005: AutoPostgreSQLBackup was written by Aaron Axelsen (with some contributions of Friedrich Lobenstock)
   * Project webpage was http://autopgsqlbackup.frozenpc.net/ (offline)

## Authors

 * Emmanuel Bouthenot (Current maintainer)
 * Friedrich Lobenstock (Contributions)
 * Aaron Axelsen (Original author)
