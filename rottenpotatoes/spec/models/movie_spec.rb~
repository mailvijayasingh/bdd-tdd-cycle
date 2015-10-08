require 'spec_helper'

describe Movie do
  describe 'search for same director' do
    it 'should find other movies with same director' do
      Movie.should_receive(:find_directors).with('Star Wars')
      Movie.find_directors('Star Wars')
    end
  end
end
