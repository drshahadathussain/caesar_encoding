# caesar-encoding

function x = caesar(character, num)
  val = double(character);
  new_val = val + num;
  encoded = char(new_val);
  x = encoded;
  disp(x);
end
